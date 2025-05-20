# Function: <code>set_buffer_uptodate</code>

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
In fs/buffer.c (ffffffff81242668)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:__end_buffer_read_notouch
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
```
```
In fs/ext4/balloc.c (ffffffff812900d2)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81292e41)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8129641e)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/page-io.c (ffffffff8129fe9f)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff812b8158)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/resize.c (ffffffff812bec80)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff812c5407)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/move_extent.c (ffffffff812d6dc1)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/indirect.c (ffffffff812d92d7)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff812ddc93)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff812dff05)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/commit.c (ffffffff812e9875)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812ec291)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff812f1a6d)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff812f6186)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff812f9461)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff8126e98b)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff812bd5eb)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812c0ee3)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/inode.c (ffffffff812c3b13)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/page-io.c (ffffffff812ce79b)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff812e6e5a)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/resize.c (ffffffff812ef33c)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/extents.c (ffffffff812f4c74)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/move_extent.c (ffffffff81306a91)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/indirect.c (ffffffff81309094)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130d872)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff8130fbab)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/commit.c (ffffffff81317e19)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff81319da0)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8131f300)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81329a09)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8132d081)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff81281ba5)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff812d2c3b)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812d6513)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/inode.c (ffffffff812d91c3)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/page-io.c (ffffffff812e457b)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff812fc9da)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/resize.c (ffffffff8130530c)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/extents.c (ffffffff8130ac24)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/move_extent.c (ffffffff8131ca35)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/indirect.c (ffffffff8131f0a4)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff8132366c)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff813259cb)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/commit.c (ffffffff8132de01)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff8132fd90)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81335382)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff8133f749)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81342dc1)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff8128f35d)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff812e4313)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff812e91bb)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff812f47d5)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff812f7d16)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff812f99ff)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff812ff8c7)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff81315616)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8131e2bd)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff81320a0c)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff81331641)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff8133cd3c)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/jbd2/commit.c (ffffffff81342f61)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff81344d3e)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8134a104)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81354374)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8135789d)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff812b1f6a)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff81308c80)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8130dc5b)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81318e47)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8131c356)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8131e03f)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81324077)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff81339e62)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff813428dd)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff81345121)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff81355af2)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff81361307)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/jbd2/commit.c (ffffffff8136758c)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff813693de)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8136e757)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81378f94)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8137c5fd)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff812d9fae)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff81336c83)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8133cbd8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81346cfc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8134a331)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8134c028)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81350a89)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff813683b6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81370763)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff8137306d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff81383eb9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff8138f44c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/jbd2/commit.c (ffffffff81395d78)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff81397b8d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8139cda8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813a79f2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813aaf71)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff812ef49c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff8134df03)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81354288)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8135eeac)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813624f4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81364168)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81369f19)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff81380839)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81388bed)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff8138b4c3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff8139c982)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813a7ea7)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/jbd2/commit.c (ffffffff813aeace)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff813b0913)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813b5b18)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813c07e2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813c3cf1)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff81310cec)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff813768a8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137ca97)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813880f9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8138a838)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8138dcc1)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81393359)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff813a9658)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b2cd9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff813b4819)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813c6bda)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813d226e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/jbd2/commit.c (ffffffff813d905f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff813daea2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813e0204)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813eb073)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813ee8f9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff81323ccc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff8138eb18)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81395197)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813a0abe)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813a3288)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff813a6721)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813abc1c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff813c2578)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813cbd47)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff813cd719)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813dff9a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813eb94e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/jbd2/commit.c (ffffffff813f3058)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff813f4ef2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813fa244)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81405665)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81408956)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff8135d37a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff813d9fcc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813dcb0f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff813dde05)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813ecd98)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813ef46b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff813f25ef)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813f7f59)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff8140ec88)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81418016)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff81419b7b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff8142c84c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffff814392ff)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/jbd2/commit.c (ffffffff8144088f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff81442248)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8144780e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81453589)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814562da)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff8136a819)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff813ebc83)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813ee54f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff813ef6f5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813fefa3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff81401bbb)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff81404d3f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81409c48)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff81422139)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8142bb13)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff8142d81b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff81445566)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff81451e28)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/fast_commit.c (ffffffff8145429c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff8145cabc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff8145e59b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81464191)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff8146fa39)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8147269a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff813712e5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff813f21c3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813f4ac4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff813f5bb4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff814052ae)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff81408102)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8140b2aa)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/inode.c (ffffffff8140fe06)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff814287fd)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff814327da)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff814344d9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff8144aebd)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
```
In fs/ext4/xattr.c (ffffffff8145755a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/fast_commit.c (ffffffff81459bcc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff81462152)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff81463e1e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81469841)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81474efb)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814780aa)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff813bfbfe)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff814441a3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81446d14)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff8144841f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81457ac6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8145aa63)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8145df24)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81462ed4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff8147c55a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8148609a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff81487f55)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff8149edcd)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff814ab66d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/fast_commit.c (ffffffff814adcbc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff814b7648)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff814b93f0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814bfce1)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff814cd466)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814cf32a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff81446887)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff814c0093)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff814c3024)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff814c496d)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff814d54e3)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff814d87c7)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff814dbcca)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/inode.c (ffffffff814e2aec)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff814ed6de)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/move_extent.c (ffffffff814fed0c)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8150945b)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff8150d529)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff81525578)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff8152ead6)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff815330d4)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/fast_commit.c (ffffffff81535bae)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff81540e12)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff8154312c)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8154a49e)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff8155924a)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8155be41)
Location: include/linux/buffer_head.h:137
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff814d599b)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff815580df)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8155b422)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff8155cead)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8156e45a)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff815715ad)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff81574c2a)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/inode.c (ffffffff8157c094)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8158754d)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/move_extent.c (ffffffff8159955b)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815a401d)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff815a82fe)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff815c2bd1)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff815ccc36)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff815d186c)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/fast_commit.c (ffffffff815d405e)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff815dff62)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff815e1f84)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff815e9dc5)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff815fc34c)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff815fdcb4)
Location: include/linux/buffer_head.h:138
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff8150c217)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:folio_create_empty_buffers
  - fs/buffer.c:folio_init_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff8158fe29)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815931d4)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff81594ccd)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff815a631a)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff815a9331)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815acafa)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/inode.c (ffffffff815b3336)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815bdc0d)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/move_extent.c (ffffffff815cfef3)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815daae2)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/resize.c (ffffffff815deb7e)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff815fa331)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff81604726)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff81609366)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/fast_commit.c (ffffffff8160bc3e)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff8161727b)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff816197b3)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81621bb2)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff816342dc)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81635c61)
Location: include/linux/buffer_head.h:141
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff81540e0e)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_commit_write
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:folio_init_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff815c89b8)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815cbec4)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff815cd97d)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff815df199)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff815e1f40)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815e5899)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/inode.c (ffffffff815ec146)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815f69cd)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/move_extent.c (ffffffff81608770)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8161330b)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/resize.c (ffffffff8161763a)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff81632f31)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:update_super_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff8163d3d8)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff816420b5)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/fast_commit.c (ffffffff816449fe)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff81650095)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff816526c0)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8165a0df)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff8166d7ac)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8166f141)
Location: include/linux/buffer_head.h:139
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffff8000103dd03c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffff800010460a98)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff800010467ed8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffff80001047410c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffff800010476b3c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffff80001047a020)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffff800010480480)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffff800010499f80)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffff8000104a405c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffff8000104a6ca4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffff8000104b8fd8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffff8000104c48b8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/jbd2/commit.c (ffff8000104ce6e0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffff8000104d086c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffff8000104d7090)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffff8000104e4988)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffff8000104e8e44)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (c05b6528)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (c06214d4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c0628c20)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c06355ac)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (c0638690)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (c063b870)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c06418b4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (c065b730)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0665f5c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (c0668ac8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (c067c674)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (c068889c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/jbd2/commit.c (c06913ac)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (c06934cc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c0699210)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (c06a36d8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c06a6d44)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (c0000000004e27d8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (c00000000057d678)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c000000000587ce0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c0000000005954d8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (c000000000599df0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c00000000059c254)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c0000000005a4b0c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (c0000000005c42b4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0000000005d1018)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (c0000000005d3360)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (c0000000005ee16c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (c0000000005fc20c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/jbd2/commit.c (c000000000607168)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (c000000000609a30)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c000000000611c6c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (c0000000006224ec)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c000000000626510)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffe00029511c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffe0002f02b6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffe0002f5c44)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffe0002ffb66)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffe000302c22)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffe0003042e0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffe0003091c4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffe00031d6d4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffe0003253ca)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffe000326c8c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffe0003358ea)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffe00033f1da)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/jbd2/commit.c (ffffffe00034605c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffe000347f42)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffe00034d00a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffe0003578b6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffe000359e08)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff8131c2ac)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff813870f8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138d777)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8139909e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8139b868)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8139ed01)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a41fc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff813bab58)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c4327)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff813c5cf9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813d857a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813e3f2e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/jbd2/commit.c (ffffffff813eb638)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff813ed4d2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813f2824)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813fdc45)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81400f36)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff8130ce4c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff81377b88)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137e207)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81389b2e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8138c2f8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8138f791)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81394c8c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff813ab5e8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b4da7)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff813b6779)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813c8ffa)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813d49ae)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/jbd2/commit.c (ffffffff813dc0b8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff813ddf52)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813e32a4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813ee6c5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813f19b6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff81319d7c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff81384bc8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138b0d7)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813968fe)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813990c8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8139c561)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a1a5c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff813b83b8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c17b7)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff813c3189)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813d5a0a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813e12ae)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/jbd2/commit.c (ffffffff813e89b8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff813ea852)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813efba4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813fafc5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813fe2b6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffffffff8132ba2f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/balloc.c (ffffffff81398754)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8139ee12)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813aab95)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813ae2bd)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813b0a74)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813b6678)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/move_extent.c (ffffffff813cd0c8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813d6917)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffffffff813d8334)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813eac8a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813f66c4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/jbd2/commit.c (ffffffff813fe210)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffffffff814001b5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814055c8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81410bed)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81413f5d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
</details>
</li>
</ul>

## Differences
