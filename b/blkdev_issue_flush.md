# Function: <code>blkdev_issue_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff813bda60)
Location: block/blk-flush.c:462
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff813bda60-ffffffff813bdae3: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814019c0)
Location: block/blk-flush.c:463
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff814019c0-ffffffff81401a4f: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8141b620)
Location: block/blk-flush.c:496
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff8141b620-ffffffff8141b6a6: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81429310)
Location: block/blk-flush.c:504
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff81429310-ffffffff81429396: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81454410)
Location: block/blk-flush.c:521
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff81454410-ffffffff814544bf: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81487860)
Location: block/blk-flush.c:526
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff81487860-ffffffff8148790f: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814a19c0)
Location: block/blk-flush.c:423
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff814a19c0-ffffffff814a1a78: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814cfb00)
Location: block/blk-flush.c:422
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff814cfb00-ffffffff814cfbc1: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814e8e60)
Location: block/blk-flush.c:433
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff814e8e60-ffffffff814e8f21: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81547de0)
Location: block/blk-flush.c:439
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff81547de0-ffffffff81547e5d: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81563b00)
Location: block/blk-flush.c:440
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff81563b00-ffffffff81563b80: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8156c260)
Location: block/blk-flush.c:438
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff8156c260-ffffffff8156c2fd: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff815d0430)
Location: block/blk-flush.c:453
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fat/file.c:fat_file_fsync
  - block/fops.c:blkdev_fsync
```
**Symbols:**

```
ffffffff815d0430-ffffffff815d04cd: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8167bc40)
Location: block/blk-flush.c:459
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fat/file.c:fat_file_fsync
  - block/fops.c:blkdev_fsync
```
**Symbols:**

```
ffffffff8167bc40-ffffffff8167bcb6: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff817384b0)
Location: block/blk-flush.c:462
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fat/file.c:fat_file_fsync
  - block/fops.c:blkdev_fsync
```
**Symbols:**

```
ffffffff817384b0-ffffffff81738526: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81774a80)
Location: block/blk-flush.c:471
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/buffer.c:generic_buffers_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fat/file.c:fat_file_fsync
  - block/fops.c:blkdev_fsync
```
**Symbols:**

```
ffffffff81774a80-ffffffff81774af6: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff817b6e00)
Location: block/blk-flush.c:469
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/buffer.c:generic_buffers_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fat/file.c:fat_file_fsync
  - block/fops.c:blkdev_fsync
```
**Symbols:**

```
ffffffff817b6e00-ffffffff817b6e76: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffff8000105e6dd0)
Location: block/blk-flush.c:433
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffff8000105e6dd0-ffff8000105e6ea0: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (c0793af8)
Location: block/blk-flush.c:433
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
c0793af8-c0793bb8: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (c00000000077b690)
Location: block/blk-flush.c:433
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
c00000000077b690-c00000000077b798: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffe000427b4c)
Location: block/blk-flush.c:433
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffe000427b4c-ffffffe000427bfa: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814e1440)
Location: block/blk-flush.c:433
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff814e1440-ffffffff814e1501: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814d1dd0)
Location: block/blk-flush.c:433
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff814d1dd0-ffffffff814d1e91: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814dd4d0)
Location: block/blk-flush.c:433
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff814dd4d0-ffffffff814dd591: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_issue_flush(struct block_device *bdev, gfp_t gfp_mask, sector_t *error_sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814f6330)
Location: block/blk-flush.c:433
Inline: False
Direct callers:
  - fs/libfs.c:generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/fat/file.c:fat_file_fsync
```
**Symbols:**

```
ffffffff814f6330-ffffffff814f63f1: blkdev_issue_flush (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>sector_t *error_sector</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
