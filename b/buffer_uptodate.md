# Function: <code>buffer_uptodate</code>

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
In fs/buffer.c (ffffffff812429fe)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff8124da6d)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff8128f4c7)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/file.c (ffffffff812924fa)
Location: include/linux/buffer_head.h:116
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81293510)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812963e3)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_walk_page_buffers
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/namei.c (ffffffff812a3efe)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81322bec)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812cbe1d)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/move_extent.c (ffffffff812d6bfa)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/mmp.c (ffffffff812d7992)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/jbd2/transaction.c (ffffffff812e8743)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff812eabed)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812eb591)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff812f0e92)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/fat/dir.c (ffffffff812f5fa2)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff812fe684)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff8126db93)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812761d9)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff812bd1f3)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/file.c (ffffffff812bfac6)
Location: include/linux/buffer_head.h:116
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812c20db)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812c87f0)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/namei.c (ffffffff812d2ed6)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff812ed8a6)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812fb74d)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/move_extent.c (ffffffff813068da)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/mmp.c (ffffffff813076f6)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/jbd2/transaction.c (ffffffff81316359)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8131857c)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81318fef)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8131e652)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff81320e49)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813295f1)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff81332681)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff81280de3)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81289edc)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff812d2843)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/file.c (ffffffff812d4cd6)
Location: include/linux/buffer_head.h:116
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812d7726)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812de3c0)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/namei.c (ffffffff812e8c26)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81303178)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813116fd)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/move_extent.c (ffffffff8131c87e)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/mmp.c (ffffffff8131d6e6)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/jbd2/transaction.c (ffffffff8132c349)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132e572)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8132efdf)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813346d2)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff81336cf9)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff8133f331)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff81348421)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff812904be)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81296ba9)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff812e3ec3)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812e6689)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/file.c (ffffffff812f1602)
Location: include/linux/buffer_head.h:116
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812f5a86)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8130242a)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813143b6)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff813153f3)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff8131857c)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81338baf)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/jbd2/transaction.c (ffffffff813415ee)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813436a1)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81344068)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813494b2)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff8134bac1)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff81353fc0)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff8135ce31)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff812b315d)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812b9e14)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff813088b3)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8130b099)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff81318bc1)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81326dba)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81338b76)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff81339bff)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff8133ce29)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8135d1b1)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/jbd2/transaction.c (ffffffff81365c20)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81367ced)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81368708)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8136db02)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff8137011a)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff81378be0)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff81381b31)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff812d9114)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812e2995)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff81336855)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81338f9d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff81346ae2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813551ff)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813670b2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff81368217)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff8136b339)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81386ad2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/jbd2/transaction.c (ffffffff81394393)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81396573)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81396f9d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8139c2b8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff8139e8d1)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813a75e9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff813b069b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff812ee5e4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812f75f6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff8134dad5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8135024d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff8135ec92)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8136d532)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8137f532)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff8138069a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813837f9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8139c960)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813ad0e3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813af2e0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813afd0d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813b5078)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff813b764f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813c03d9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff813c9cfb)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff8130fddb)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81317c30)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff813764b8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81378eeb)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff81387ef5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81396b23)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813a89b0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff813a94ec)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff813acfa5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813c6bb8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813d739b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d980a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813da269)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813df6c8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff813e1df1)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813eabe9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff813f487b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff81322dab)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8132aaab)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff8138e728)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813912ab)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff813a08a5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813af553)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813c18c0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff813c240c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff813c5edd)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813dff78)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813f13cb)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f37fa)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f42b9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813f9788)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff813fbe21)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff81404c89)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff8140e74b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff8135d892)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff813645bd)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff813d9ee8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813dcb43)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff813ebfe4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:recently_deleted
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813fb5c3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8140dc1d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff8140eafb)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff8141232e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8142c82a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff8143c901)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff81440b21)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814417be)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff81447066)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/fat/dir.c (ffffffff81452af3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff8145c53b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff8136b482)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff813715bf)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff813ebbb4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813ee583)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff813fe194)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:recently_deleted
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8140dd05)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mballoc.c (ffffffff8141c0af)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff81421209)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff81422003)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff814257ce)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81445544)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/transaction.c (ffffffff81458c81)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff8145cd56)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8145d9ae)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff814635c6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/dir.c (ffffffff8146efa3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff8147843b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff81371d22)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8137888f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff813f20f4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813f4b47)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff814046f8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81413ec9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mballoc.c (ffffffff8142232c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff814279b9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff814286c7)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff8142c3dd)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8144ae5f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
```
In fs/jbd2/transaction.c (ffffffff814603ab)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81462764)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814632be)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff81468726)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/dir.c (ffffffff814745b0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff8147deab)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff813c0d42)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff813c51b9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff814440d4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81446d97)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff81456ea8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81467235)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mballoc.c (ffffffff81475a6d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff8147b684)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff8147c412)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff8148029e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8149ed6f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/jbd2/transaction.c (ffffffff814b582e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814b7c5a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b87fe)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff814be1d6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/dir.c (ffffffff814cb2dc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff814d564b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff814447ab)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8144c14f)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff814bffcb)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff814c30b6)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff814d498b)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff814e6e0e)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff814ed4c6)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff814f7d48)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff814fdb54)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff814febee)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff815031e9)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff815254fd)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff8152eada)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/jbd2/transaction.c (ffffffff8153d444)
Location: include/linux/buffer_head.h:152
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff8154170b)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81542346)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff81549916)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/dir.c (ffffffff815573ab)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff8156272a)
Location: include/linux/buffer_head.h:152
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff814d3471)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__breadahead
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff814da4f9)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff815572d2)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8155b44f)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff8156d63f)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8158061a)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff81587326)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff81592308)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff815983d8)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff8159943b)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff8159dd29)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff815c2b5d)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff815ccc42)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/jbd2/transaction.c (ffffffff815dbc74)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff815e0351)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff815e0fa9)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff815e885d)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/dir.c (ffffffff815f8f78)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff81605107)
Location: include/linux/buffer_head.h:164
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In mm/migrate.c (ffffffff81469bb0)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff8150a701)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__breadahead
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8150ead0)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff8158f152)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8159326d)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff815a552f)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff815b7bda)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815bd9e6)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff815c93ea)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff815cedba)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/move_extent.c (ffffffff815cfd91)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff815d458d)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff815fa2bd)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff81604732)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/jbd2/transaction.c (ffffffff81613734)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff81617bfd)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81618899)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8162045d)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/dir.c (ffffffff81630ed8)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff8163d017)
Location: include/linux/buffer_head.h:167
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In mm/migrate.c (ffffffff81498b3d)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff8153f6b1)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:__block_commit_write
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__breadahead
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff815433cd)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff815c7e62)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815cbf5d)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff815de39f)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff815f0963)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815f67a6)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff816021ca)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff8160764a)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/move_extent.c (ffffffff8160860e)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff8160cc3d)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81632ebd)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:update_super_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff8163d3e4)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/jbd2/transaction.c (ffffffff8164c538)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff81650aef)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81651818)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8165942d)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/dir.c (ffffffff8166a388)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff81676587)
Location: include/linux/buffer_head.h:165
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffff8000103dbecc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffff8000103e6390)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffff8000104609a0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffff800010463e48)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffff800010474060)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffff800010483e74)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffff800010499094)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffff800010499e40)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffff80001049d9b0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffff8000104b8fa8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffff8000104cb390)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ce984)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104cfbac)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffff8000104d5e88)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffff8000104d99cc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffff8000104e3988)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffff8000104ef398)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (c05b5200)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (c05bdd8c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (c0621140)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (c062441c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (c0634bf8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c0645494)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (c065aa0c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (c065b638)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (c065f514)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (c067c644)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (c068ed7c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c0691860)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0692660)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (c0697890)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (c069b328)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (c06a2ba0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (c06acea4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (c0000000004e3d10)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (c0000000004ec2a4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (c00000000057cff0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (c000000000581154)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (c0000000005953b0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c0000000005a8f30)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (c0000000005c31f0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (c0000000005c40f8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (c0000000005c9094)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (c0000000005ee0dc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (c000000000604440)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c000000000607918)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c000000000608a60)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (c000000000610920)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (c000000000614404)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (c000000000620ba4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (c00000000062e638)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffe000294420)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffe00029b59e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffe0002efe6e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffe0002f2582)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffe0002ffaa2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffe00030c426)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffe00031cc16)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffe00031d5f6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffe000320666)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffe0003358c0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffe0003441c0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffe000346702)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe000347254)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffe00034c2ee)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffe00034eb68)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffe000356f84)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffe00035f3a2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff8131b38b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8132308b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff81386d08)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8138988b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff81398e85)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813a7b33)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b9ea0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff813ba9ec)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff813be4bd)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813d8558)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813e99ab)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813ebdda)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ec899)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813f1d68)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff813f4401)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813fd269)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff81406d2b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff8130bf2b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81313c2b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff81377798)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8137a31b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff81389915)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813985c3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813aa930)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff813ab47c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff813aef4d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813c8fd8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813da42b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dc85a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dd319)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813e27e8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff813e4e81)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813edce9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff813f77ab)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff81318e5b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81320b5b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff813847d8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813871eb)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff813966e5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813a5393)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b7700)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff813b824c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff813bbabd)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813d59e8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813e6d2b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e915a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813e9c19)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813ef0e8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff813f1781)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813fa5e9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff814040ab)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
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
In fs/buffer.c (ffffffff8132aa8b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8133287b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff81398358)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8139aec5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff813aa945)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813b9ad3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813cc403)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff813ccf4c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff813d0a4f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813eac68)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813fc30b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fea3f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ff569)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff81404ab5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
```
In fs/squashfs/block.c (ffffffff8140738c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff81410249)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff81419d19)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
</details>
</li>
</ul>

## Differences
