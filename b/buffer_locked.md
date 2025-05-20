# Function: <code>buffer_locked</code>

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
In fs/buffer.c (ffffffff81242ff9)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff8124d81e)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff8128f4b8)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81293847)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81296474)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/namei.c (ffffffff812a3ee7)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81322bd8)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/ext4/extents.c (ffffffff812c5bd3)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff812d7980)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/jbd2/transaction.c (ffffffff812e820b)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff812eabd4)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812eb5d8)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff812eccda)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
```
```
In fs/jbd2/journal.c (ffffffff812f0f9c)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/misc.c (ffffffff812fe66c)
Location: include/linux/buffer_head.h:119
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
In fs/buffer.c (ffffffff8126cf25)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81275f80)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff812bd3a2)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812c0e0a)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812c3a6d)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/namei.c (ffffffff812d2ec0)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff812ed882)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/extents.c (ffffffff812f541a)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff813076e4)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/jbd2/transaction.c (ffffffff81315e6f)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff81318563)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8131903a)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8131ad1e)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8131e75d)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff81320e36)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff81332669)
Location: include/linux/buffer_head.h:119
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
In fs/buffer.c (ffffffff812801b5)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81289c6a)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff812d29f2)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812d643a)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812d911d)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/namei.c (ffffffff812e8c10)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81303154)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/extents.c (ffffffff8130b3ca)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff8131d6d4)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/jbd2/transaction.c (ffffffff8132be5f)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff8132e559)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8132f02a)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff81330d0e)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813347dd)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff81336ce6)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff81348409)
Location: include/linux/buffer_head.h:119
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
In fs/buffer.c (ffffffff8128da95)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8129694f)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff812e4006)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff812e9b5c)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff812f46fc)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812ff7e6)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813143a3)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8131856d)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81338b83)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/jbd2/transaction.c (ffffffff8134105f)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff81343688)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813440b3)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff81345c6e)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813495e5)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff8134baaf)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff8135ce19)
Location: include/linux/buffer_head.h:119
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
In fs/buffer.c (ffffffff812b0666)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812b9baf)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81308996)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8130e5fc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81318dba)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81323f96)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff81338b63)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8133ce1a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8135d19d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/jbd2/transaction.c (ffffffff8136567f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff81367cd2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81368753)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8136a301)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8136dc35)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff81370107)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff81381b19)
Location: include/linux/buffer_head.h:120
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
In fs/buffer.c (ffffffff812d8445)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812e2723)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81336925)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8133a8c4)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81346de9)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8135096a)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813670a3)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8136b32e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81386ac3)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/jbd2/transaction.c (ffffffff81393e2b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff81396566)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81396fed)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813989f1)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8139c404)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff8139e8ed)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff813b06b5)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff812ed915)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812f738f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff8134dba5)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81351c47)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8135ef99)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81369dfa)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff8137f523)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813837ee)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8139f5c3)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813acb4b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff813af2d3)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813afd5d)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813b1761)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813b51c4)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813b766b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff813c9d15)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff8130f0e5)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff813179be)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81376580)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137b548)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813881db)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8139324c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813a89a2)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813acf99)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813c929b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813d6dab)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff813d97fd)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813da2b8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813dbd8f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813df868)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813e1e0e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff813f4895)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff81322045)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8132a83e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff8138e7f0)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81393a18)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813a0ba0)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813abc8b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813c18b2)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813c5ed2)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813e2649)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813f0e9b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff813f37ed)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f4308)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813f5dff)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813f9928)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813fbe3e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff8140e765)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff8135d885)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff813644f2)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff813d9bc3)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/extents.c (ffffffff813dfc25)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813ece7e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813f7fd4)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff8140dc0f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81412323)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8142e703)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff8143e365)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff81440b14)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81441802)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8144319f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8144720d)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/misc.c (ffffffff8145c555)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff8136b475)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff813714f4)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff813ebba9)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/extents.c (ffffffff813f14e5)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/inode.c (ffffffff81409cb8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff814211eb)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff814257c3)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81444d95)
Location: include/linux/buffer_head.h:123
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8145a605)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff8145cd49)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8145d9f2)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8145f2ff)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8146376d)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff81478455)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff81371d15)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff813787c4)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff813f20e9)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/extents.c (ffffffff813f796e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/inode.c (ffffffff8140fe7c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff8142799b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8142c3d2)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8144a6b5)
Location: include/linux/buffer_head.h:123
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8145fea5)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff81462757)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81463302)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff81464b6f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814688bb)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff8147dec5)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff813c0d35)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff813c50d5)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff814440c9)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/extents.c (ffffffff81449454)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/inode.c (ffffffff81462f33)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff8147b666)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81480293)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8149e195)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/jbd2/transaction.c (ffffffff814b5348)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff814b7c4d)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b8842)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff814ba4cf)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814be36b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff814d5665)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff81444795)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff8144c04a)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff814bffc0)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/extents.c (ffffffff814c53ca)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/inode.c (ffffffff814e29b8)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff814fdb1e)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815031de)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8152553d)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/jbd2/transaction.c (ffffffff8153ec74)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff815416fe)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81542394)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff81544309)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81549a6e)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff81562744)
Location: include/linux/buffer_head.h:122
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
In fs/buffer.c (ffffffff814d3035)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff814da4d8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff8155728a)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/extents.c (ffffffff8155d930)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/inode.c (ffffffff8157be03)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff81598309)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8159dd1e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff815c2b96)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/jbd2/transaction.c (ffffffff815dd63f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff815e0344)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff815e1018)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff815e32f9)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff815e9cb8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff81605122)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff81509c55)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff8150e9fe)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff8158f10a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/extents.c (ffffffff81595749)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/inode.c (ffffffff815b3203)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff815ced7c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff815d4582)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff815fa2f6)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/jbd2/transaction.c (ffffffff8161595d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff81617bf0)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81618908)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a522)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81621a9f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff8163d032)
Location: include/linux/buffer_head.h:126
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
In fs/buffer.c (ffffffff8153ea85)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff81543312)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff815c7e1a)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/extents.c (ffffffff815ce3f8)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/inode.c (ffffffff815ec004)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff8160760c)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff8160cc32)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81632ef6)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/jbd2/transaction.c (ffffffff8164e789)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff81650ae2)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81651887)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8165345c)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81659fc8)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff816765a2)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffff8000103dadb4)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffff8000103e601c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffff800010460b64)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff8000104666f0)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffff8000104741e8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffff800010480518)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffff800010499084)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffff80001049d9a8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffff8000104bba00)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffff8000104cac14)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffff8000104ce978)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104cfc00)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffff8000104d1afc)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffff8000104d6030)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffff8000104d99e8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffff8000104ef388)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (c05b414c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (c05bdb80)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (c0621234)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c06271ec)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c0635834)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c0641958)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (c065a9fc)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (c065f508)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (c067f0d8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (c068e60c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (c0691850)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c06926b0)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (c0694518)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c0697a8c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (c069b344)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (c06acec0)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (c0000000004e3cfc)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (c0000000004ec19c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (c00000000057d0c4)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c000000000584540)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c000000000595614)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c0000000005a4bb4)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (c0000000005c31e0)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (c0000000005c9088)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (c0000000005f1874)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (c000000000603b68)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (c0000000006079ec)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c000000000608ad4)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (c00000000060b0b4)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c000000000610c1c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (c000000000614424)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (c00000000062e61c)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffe0002937d8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffe00029b3fe)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffe0002efefc)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffe0002f47b6)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffe0002ffd50)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffe000309244)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffe00031cc0a)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffe00032065c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffe000337c70)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffe000343ca2)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffe0003466ec)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe000347296)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffe000348dfc)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffe00034c482)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffe00034eb86)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffe00035f394)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff8131a625)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81322e1e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81386dd0)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138bff8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81399180)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813a426b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813b9e92)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813be4b2)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813dac29)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813e947b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff813ebdcd)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ec8e8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813ee3df)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813f1f08)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813f441e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff81406d45)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff8130b1c5)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff813139be)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81377860)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137ca88)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81389c10)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81394cfb)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813aa922)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813aef42)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813cb6a9)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813d9efb)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff813dc84d)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dd368)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813dee5f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813e2988)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813e4e9e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff813f77c5)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff813180f5)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff813208ee)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff813848a0)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81389958)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813969e0)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813a1acb)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813b76f2)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813bbab2)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813d80c9)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813e67fb)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff813e914d)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813e9c68)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813eb75f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813ef288)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813f179e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff814040c5)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff81329d15)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8133260e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff8139841b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8139d666)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813aac91)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813b66f8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813cc3f8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813d0a44)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813ed364)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff813fbd73)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
```
```
In fs/jbd2/commit.c (ffffffff813fea37)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ff5b3)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8140110f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81404c52)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff814073a5)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff81419d2e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
</details>
</li>
</ul>

## Differences
