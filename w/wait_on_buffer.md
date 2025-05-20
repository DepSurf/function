# Function: <code>wait_on_buffer</code>

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
In fs/buffer.c (ffffffff8124424e)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff8128f4b3)
Location: include/linux/buffer_head.h:340
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81293842)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8129646f)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/namei.c (ffffffff812a3ee2)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81322bd3)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/ext4/mmp.c (ffffffff812d797b)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff812eabcf)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812eb5d3)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff812ecf61)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff812f0f97)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/misc.c (ffffffff812fe667)
Location: include/linux/buffer_head.h:340
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
In fs/buffer.c (ffffffff8126eaaf)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff812bc9c3)
Location: include/linux/buffer_head.h:344
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812c0e05)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812c3a68)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/namei.c (ffffffff812d2ebb)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff812ed87d)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/mmp.c (ffffffff813076df)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff8131855e)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81319035)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8131a9b9)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8131e758)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff81320e31)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff81332664)
Location: include/linux/buffer_head.h:344
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
In fs/buffer.c (ffffffff81281cc6)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff812d2013)
Location: include/linux/buffer_head.h:347
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812d6435)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812d9118)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/namei.c (ffffffff812e8c0b)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8130314f)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/mmp.c (ffffffff8131d6cf)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff8132e554)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8132f025)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813309a5)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813347d8)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff81336ce1)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff81348404)
Location: include/linux/buffer_head.h:347
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
In fs/buffer.c (ffffffff8128f45a)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff812e3684)
Location: include/linux/buffer_head.h:348
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812f46f7)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812ff7e1)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff8131439e)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81318568)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81338b7e)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/jbd2/commit.c (ffffffff81343683)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813440ae)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8134590c)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813495e0)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff8134baaa)
Location: include/linux/buffer_head.h:348
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff8135ce14)
Location: include/linux/buffer_head.h:348
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
In fs/buffer.c (ffffffff812b208e)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81308074)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81318f41)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81323f91)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff81338b5e)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8133ce15)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8135d198)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/jbd2/commit.c (ffffffff81367ccd)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8136874e)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff81369fb9)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8136dc30)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff81370102)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff81381b14)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffff812d9fe5)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81335f63)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81346de4)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81350965)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff8136709e)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8136b329)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81386abe)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/jbd2/commit.c (ffffffff81396566)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81396fe8)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8139874d)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8139c3ff)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff8139e8e8)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff813b06b0)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffff812ef4d3)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff8134d1e3)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8135ef94)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81369df5)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff8137f51e)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813837e9)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8139f5be)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813af2d3)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813afd58)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813b14bd)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813b51bf)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813b7666)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff813c9d10)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffff81310d23)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81375bcd)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813881d6)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81393247)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813a899d)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813acf94)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813c9296)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813d97fd)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813da2b3)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813dbab8)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813df863)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813e1e09)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff813f4890)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffff81323d03)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff8138de3d)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813a0b9b)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813abc86)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813c18ad)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813c5ecd)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813e2644)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813f37ed)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f4303)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813f5b08)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813f9923)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813fbe39)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff8140e760)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffff8135d880)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:osync_buffers_list
```
```
In fs/ext4/balloc.c (ffffffff813d933d)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813ece79)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813f7fcf)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff8140dc0a)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8141231e)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8142e6fe)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff81440b14)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814417fd)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff81442eab)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81447208)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/misc.c (ffffffff8145c550)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffff8136b470)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:osync_buffers_list
```
```
In fs/ext4/balloc.c (ffffffff813eafcd)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81409cb3)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff814211e6)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff814257be)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81444e52)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff8145cd49)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8145d9ed)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8145f02d)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81463768)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff81478450)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffff81371d10)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/balloc.c (ffffffff813f1515)
Location: include/linux/buffer_head.h:352
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8140fe77)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff81427996)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8142c3cd)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8144a772)
Location: include/linux/buffer_head.h:352
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81462757)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814632fd)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff814648ab)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814688b6)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff8147dec0)
Location: include/linux/buffer_head.h:352
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
In fs/buffer.c (ffffffff813c0d30)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/balloc.c (ffffffff81443515)
Location: include/linux/buffer_head.h:352
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81462f2e)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff8147b661)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8148028e)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff8149e243)
Location: include/linux/buffer_head.h:352
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff814b7c4d)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b883d)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff814b9f0c)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814be366)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff814d5660)
Location: include/linux/buffer_head.h:352
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
In fs/buffer.c (ffffffff814447c9)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/balloc.c (ffffffff814bf345)
Location: include/linux/buffer_head.h:374
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e29b3)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff814fdb19)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815031d9)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81525538)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
```
```
In fs/jbd2/commit.c (ffffffff815416fe)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8154238f)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff81543c93)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81549a69)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff8156273f)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wait_on_buffer(struct buffer_head *bh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d3079)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/balloc.c (ffffffff81557285)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/inode.c (ffffffff8157bdfe)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff81598304)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8159dd19)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff815c2b91)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
```
```
In fs/jbd2/commit.c (ffffffff815e0344)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff815e1013)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff815e2c03)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
Direct callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff815e9cb3)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff8160511d)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff815e2420-ffffffff815e2458: wait_on_buffer (STB_LOCAL)
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
In fs/buffer.c (ffffffff81509c99)
Location: include/linux/buffer_head.h:394
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/balloc.c (ffffffff8158f105)
Location: include/linux/buffer_head.h:394
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/inode.c (ffffffff815b31fe)
Location: include/linux/buffer_head.h:394
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff815ced77)
Location: include/linux/buffer_head.h:394
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff815d457d)
Location: include/linux/buffer_head.h:394
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff815fa2f1)
Location: include/linux/buffer_head.h:394
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
```
```
In fs/jbd2/commit.c (ffffffff81617bf0)
Location: include/linux/buffer_head.h:394
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81618903)
Location: include/linux/buffer_head.h:394
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a51d)
Location: include/linux/buffer_head.h:394
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81621a9a)
Location: include/linux/buffer_head.h:394
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff8163d02d)
Location: include/linux/buffer_head.h:394
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
In fs/buffer.c (ffffffff8153eac9)
Location: include/linux/buffer_head.h:385
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/balloc.c (ffffffff815c7e15)
Location: include/linux/buffer_head.h:385
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/inode.c (ffffffff815ebfff)
Location: include/linux/buffer_head.h:385
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
```
```
In fs/ext4/mmp.c (ffffffff81607607)
Location: include/linux/buffer_head.h:385
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff8160cc2d)
Location: include/linux/buffer_head.h:385
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81632ef1)
Location: include/linux/buffer_head.h:385
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
```
```
In fs/jbd2/commit.c (ffffffff81650ae2)
Location: include/linux/buffer_head.h:385
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81651882)
Location: include/linux/buffer_head.h:385
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff81653457)
Location: include/linux/buffer_head.h:385
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81659fc3)
Location: include/linux/buffer_head.h:385
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/misc.c (ffffffff8167659d)
Location: include/linux/buffer_head.h:385
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
In fs/buffer.c (ffff8000103dd0b8)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffff80001045ff34)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffff8000104741e4)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffff800010480514)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffff800010499080)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffff80001049d9a4)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffff8000104bb9fc)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffff8000104ce978)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104cfbfc)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffff8000104d1500)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffff8000104d602c)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffff8000104d99e4)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffff8000104ef384)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (c05b6574)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/balloc.c (c0620744)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (c0635830)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c0641954)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (c065a9f8)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (c065f504)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (c067f0d4)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (c0691850)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c06926ac)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (c0694170)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c0697a88)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (c069b340)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (c06acebc)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (c0000000004e3cf4)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (c00000000057c278)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (c00000000059560c)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c0000000005a4bac)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (c0000000005c31d8)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (c0000000005c9080)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (c0000000005f186c)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (c0000000006079ec)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c000000000608acc)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (c00000000060ab08)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c000000000610c14)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (c00000000061441c)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (c00000000062e614)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffe0002951e8)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffe0002ef61a)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffe0002ffd48)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffe00030923c)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffe00031cc02)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffe000320654)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffe000337c68)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffe0003466e4)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe00034728e)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffe0003489fc)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffe00034c47a)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffe00034eb7e)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffe00035f38c)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffff8131c2e3)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff8138641d)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8139917b)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813a4266)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813b9e8d)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813be4ad)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813dac24)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813ebdcd)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ec8e3)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813ee0e8)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813f1f03)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813f4419)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff81406d40)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffff8130ce83)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81376ead)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81389c0b)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81394cf6)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813aa91d)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813aef3d)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813cb6a4)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813dc84d)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dd363)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813deb68)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813e2983)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813e4e99)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff813f77c0)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffff81319db3)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81383eed)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813969db)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813a1ac6)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813b76ed)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813bbaad)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813d80c4)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813e914d)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813e9c63)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff813eb468)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813ef283)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff813f1799)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff814040c0)
Location: include/linux/buffer_head.h:350
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
In fs/buffer.c (ffffffff8132ba90)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81397a5d)
Location: include/linux/buffer_head.h:350
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813aac91)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff813b66f8)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mmp.c (ffffffff813cc3f8)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813d0a44)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff813ed364)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813fea37)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ff5b3)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff81400e22)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81404c52)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/squashfs/block.c (ffffffff814073a5)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/misc.c (ffffffff81419d2e)
Location: include/linux/buffer_head.h:350
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
