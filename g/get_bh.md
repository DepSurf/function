# Function: <code>get_bh</code>

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
In mm/migrate.c (ffffffff811f0ee6)
Location: include/linux/buffer_head.h:271
Inline: True
```
```
In fs/buffer.c (ffffffff81242e07)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81290067)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81293820)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81295cb9)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:bget_one
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
```
In fs/ext4/mmp.c (ffffffff812d7948)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff812dd2a4)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff812df8e3)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
```
```
In fs/jbd2/transaction.c (ffffffff812e8124)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
```
```
In fs/jbd2/commit.c (ffffffff812eae1f)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff812ecde6)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff812f198e)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/fat/dir.c (ffffffff812f64d5)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_add_entries
```
```
In fs/fat/fatent.c (ffffffff812f8e42)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In mm/migrate.c (ffffffff81210181)
Location: include/linux/buffer_head.h:275
Inline: True
```
```
In fs/buffer.c (ffffffff8126dbc6)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/balloc.c (ffffffff812bd57e)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812c0ded)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812c917b)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mmp.c (ffffffff813076aa)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff8130d620)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/inline.c (ffffffff8130f722)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/jbd2/transaction.c (ffffffff81317234)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff8131887f)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8131a83d)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81320a0f)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff8132a72b)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff8132ca52)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In mm/migrate.c (ffffffff812222b1)
Location: include/linux/buffer_head.h:278
Inline: True
```
```
In fs/buffer.c (ffffffff81280e16)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff812d2bce)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812d641d)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812dedbb)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mmp.c (ffffffff8131d69a)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff813234db)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/inline.c (ffffffff8132554a)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/jbd2/transaction.c (ffffffff8132d224)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff8132e875)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8133082d)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813368bf)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff8134046b)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff81342792)
Location: include/linux/buffer_head.h:278
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In mm/migrate.c (ffffffff8122db51)
Location: include/linux/buffer_head.h:279
Inline: True
```
```
In fs/buffer.c (ffffffff8128e6f6)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff812e4185)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812f46df)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff812f95d2)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81302de6)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mmp.c (ffffffff81314368)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff8133c904)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff813423f4)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff813439ec)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8134572c)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8134b57a)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff81355047)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff81357447)
Location: include/linux/buffer_head.h:279
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In mm/migrate.c (ffffffff812496d1)
Location: include/linux/buffer_head.h:281
Inline: True
```
```
In fs/buffer.c (ffffffff812b12e6)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81308b33)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81318f29)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8131dc0a)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813277d6)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mmp.c (ffffffff81338b28)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff81360ea0)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff81366a24)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff8136803f)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81369dd2)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8136fbaa)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff81379c67)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff8137c099)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In mm/migrate.c (ffffffff8126ed1f)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff812d914a)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81336b6d)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81346dcc)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8134bbed)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8135547b)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mmp.c (ffffffff81367068)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff8138f838)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff81395114)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff81396952)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81398516)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8139e0cd)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff813a846d)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff813aac17)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff812ee61a)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff8134dded)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8135ef7c)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff81363d2d)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8136d7aa)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mmp.c (ffffffff8137f4e8)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff813a82f3)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff813ade84)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff813af6bb)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813b1286)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813b6e3d)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff813c14ad)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff813c39f7)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff8130fe11)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff813767ce)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813881bf)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8138d32e)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81396dd6)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (ffffffff813a8968)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff813d2813)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff813d81f5)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff813d9c09)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813db8f1)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813e1538)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff813ebd09)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff813ee0bf)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff81322de1)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff8138ea3e)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813a0b84)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff813a5d8e)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813af806)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (ffffffff813c1878)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff813ebef3)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff813f22d5)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff813f3be4)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813f5941)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813fb588)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff81405e29)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff814081df)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff8135d859)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/balloc.c (ffffffff813da0d0)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813ece65)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff813f231e)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813fb81a)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (ffffffff8140dbd5)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff814393d8)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff8143e25a)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff81440f5d)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81442ce7)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81448d1b)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff81453ef7)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff81455c93)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff8136b449)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/inline.c (ffffffff81404a6e)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8140df8d)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (ffffffff814211d0)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81444dc5)
Location: include/linux/buffer_head.h:275
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81451f01)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff8145a4fa)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff8145d15e)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8145eec1)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814658bb)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff814703a7)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff81472053)
Location: include/linux/buffer_head.h:275
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff81371ce9)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/inline.c (ffffffff8140b02e)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8141414d)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (ffffffff81427980)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff8144a6e5)
Location: include/linux/buffer_head.h:277
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81457633)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff8145fd9a)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff81462a87)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8146473f)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8146b06b)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff8147582a)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff81477a70)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff813c0d09)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/inline.c (ffffffff8145dc98)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff814674ad)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
```
In fs/ext4/mmp.c (ffffffff8147b64b)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff8149e1c6)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff814ab4dd)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff814b523a)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff814b7f7d)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff814b9d13)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814c198b)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff814cd85b)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff814ced3b)
Location: include/linux/buffer_head.h:277
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff814447af)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/inline.c (ffffffff814db4ab)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff814e70ac)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
```
In fs/ext4/mmp.c (ffffffff814fdb03)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81525504)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff8153347c)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff8153eb80)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff81541b4d)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81543a7c)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8154c3b6)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff8155984c)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff8155b701)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff814d33e6)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/inline.c (ffffffff8157412b)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81580a72)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
```
In fs/ext4/mmp.c (ffffffff815982f3)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff815c2b62)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff815d19d0)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff815dd530)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff815e0799)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff815e29ec)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff815ec1d6)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff815fc95c)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff815fd571)
Location: include/linux/buffer_head.h:312
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff8150a676)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/inline.c (ffffffff815abf7b)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815b8022)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
```
In fs/ext4/mmp.c (ffffffff815ced66)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/super.c (ffffffff815fa2c2)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff8160949a)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff81614fd0)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff81618046)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a450)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81623cb6)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff816348ec)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff81635511)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff8153f626)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/inline.c (ffffffff815e4d1b)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815f0dc2)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
```
In fs/ext4/mmp.c (ffffffff816075f6)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/super.c (ffffffff81632ec2)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff816421e9)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff8164ddc0)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff81650f7a)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81653390)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8165cd56)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff8166ddcc)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff8166e9f1)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffff8000103dbf14)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffff800010460e08)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffff8000104741c4)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffff800010479600)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffff8000104804dc)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (ffff800010499030)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffff8000104c4e40)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffff8000104cca0c)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffff8000104cf05c)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffff8000104d15b4)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffff8000104d8c60)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffff8000104e4cc4)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffff8000104e8d5c)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (c05b5278)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/ext4/balloc.c (c0621648)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (c0635808)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (c063aba4)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (c06457fc)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (c065a980)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (c0688ee8)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (c06902d8)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (c0691e24)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (c0693f3c)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c069ab48)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (c06a40a0)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (c06a62d0)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (c0000000004e3cbc)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (c00000000057d43c)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (c0000000005955e8)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (c00000000059ba90)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (c0000000005a93ac)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (c0000000005c3170)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (c0000000005fc998)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (c00000000060611c)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (c000000000607efc)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (c00000000060a8b0)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c000000000613b38)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (c000000000622858)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (c000000000625cd8)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffe000294412)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffe0002f018a)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffe0002ffd30)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffe000303eaa)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffe00030c726)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (ffffffe00031cbc2)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffe00033f6a6)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffe000345382)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffe000346bc8)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffe00034874e)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffe00034e65a)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffe000357fe6)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffe000359972)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff8131b3c1)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff8138701e)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81399164)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8139e36e)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813a7de6)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (ffffffff813b9e58)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff813e44d3)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff813ea8b5)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff813ec1c4)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813edf21)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813f3b68)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff813fe409)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff814007bf)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff8130bf61)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81377aae)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81389bf4)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8138edfe)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81398876)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (ffffffff813aa8e8)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff813d4f53)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff813db335)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff813dcc44)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813de9a1)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813e45e8)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff813eee89)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff813f123f)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff81318e91)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81384aee)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813969c4)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8139bbce)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813a5646)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (ffffffff813b76b8)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff813e1853)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff813e7c35)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff813e9544)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813eb2a1)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813f0ee8)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff813fb789)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff813fdb3f)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
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
In fs/buffer.c (ffffffff8132aac1)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/ext4/balloc.c (ffffffff81398667)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813aac75)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff813b00ee)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813b9d86)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mmp.c (ffffffff813cc3c8)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff813f6c61)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff813fd435)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
```
```
In fs/jbd2/commit.c (ffffffff813fee47)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81400c34)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81406a64)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff814113a9)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff814137ef)
Location: include/linux/buffer_head.h:281
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
```
</details>
</li>
</ul>

## Differences
