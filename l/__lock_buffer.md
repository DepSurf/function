# Function: <code>__lock_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81243ab0)
Location: fs/buffer.c:68
Inline: True
Inline callers:
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:nobh_write_begin
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/resize.c:update_backups
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
**Symbols:**

```
ffffffff81243ab0-ffffffff81243ae8: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126f37e)
Location: fs/buffer.c:69
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
**Symbols:**

```
ffffffff8126bc80-ffffffff8126bcb5: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128257d)
Location: fs/buffer.c:70
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
**Symbols:**

```
ffffffff8127edc0-ffffffff8127edf5: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128fc34)
Location: fs/buffer.c:70
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
**Symbols:**

```
ffffffff8128c590-ffffffff8128c5c5: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b295e)
Location: fs/buffer.c:70
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
**Symbols:**

```
ffffffff812af1a0-ffffffff812af1d5: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812da84d)
Location: fs/buffer.c:63
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - mm/migrate.c:buffer_migrate_page
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
**Symbols:**

```
ffffffff812d6a60-ffffffff812d6a96: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812efd2d)
Location: fs/buffer.c:63
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
**Symbols:**

```
ffffffff812ec0a0-ffffffff812ec0d6: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813115d3)
Location: fs/buffer.c:64
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
**Symbols:**

```
ffffffff8130d6f0-ffffffff8130d729: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813245b3)
Location: fs/buffer.c:64
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff813206c0-ffffffff813206f9: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135d8f6)
Location: fs/buffer.c:67
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff813595a0-ffffffff813595db: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136b4e6)
Location: fs/buffer.c:67
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_update_super_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81367990-ffffffff813679cb: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81371d86)
Location: fs/buffer.c:67
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8136dd60-ffffffff8136dd9b: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c0da6)
Location: fs/buffer.c:67
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff813bced0-ffffffff813bcf0b: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81445087)
Location: fs/buffer.c:67
Inline: True
Inline callers:
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81442ef0-ffffffff81442f37: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d344b)
Location: fs/buffer.c:67
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
Direct callers:
  - mm/migrate.c:__buffer_migrate_folio
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:__ext4_xattr_check_block
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff814d26f0-ffffffff814d2737: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150a6db)
Location: fs/buffer.c:68
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
Direct callers:
  - mm/migrate.c:__buffer_migrate_folio
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:check_xattrs
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81509000-ffffffff81509047: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153f68b)
Location: fs/buffer.c:69
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
Direct callers:
  - mm/migrate.c:__buffer_migrate_folio
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:check_xattrs
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8153d7d0-ffffffff8153d817: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103dd6b0)
Location: fs/buffer.c:64
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffff8000103d8120-ffff8000103d81b4: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b6e30)
Location: fs/buffer.c:64
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
c05b23f8-c05b2444: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e3db0)
Location: fs/buffer.c:64
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
c0000000004ddf80-c0000000004de000: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe0002958f2)
Location: fs/buffer.c:64
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffe0002920b2-ffffffe0002920fa: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131cb93)
Location: fs/buffer.c:64
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81318ca0-ffffffff81318cd9: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130d733)
Location: fs/buffer.c:64
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81309890-ffffffff813098c9: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131a663)
Location: fs/buffer.c:64
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81316770-ffffffff813167a9: __lock_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __lock_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132c379)
Location: fs/buffer.c:64
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff813286d0-ffffffff813286fa: __lock_buffer (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
