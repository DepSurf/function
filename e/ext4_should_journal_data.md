# Function: <code>ext4_should_journal_data</code>

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
In fs/ext4/file.c (ffffffff81292247)
Location: fs/ext4/ext4_jbd2.h:411
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff81292c6a)
Location: fs/ext4/ext4_jbd2.h:411
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81298237)
Location: fs/ext4/ext4_jbd2.h:411
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/ext4/super.c (ffffffff812b8ade)
Location: fs/ext4/ext4_jbd2.h:411
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/extents.c (ffffffff812c6ea4)
Location: fs/ext4/ext4_jbd2.h:411
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812cbc0a)
Location: fs/ext4/ext4_jbd2.h:411
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/move_extent.c (ffffffff812d739f)
Location: fs/ext4/ext4_jbd2.h:411
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/indirect.c (ffffffff812d8a46)
Location: fs/ext4/ext4_jbd2.h:411
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_direct_IO
```
```
In fs/ext4/inline.c (ffffffff812e0dd0)
Location: fs/ext4/ext4_jbd2.h:411
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
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
In fs/ext4/file.c (ffffffff812bf73c)
Location: fs/ext4/ext4_jbd2.h:430
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff812c018d)
Location: fs/ext4/ext4_jbd2.h:430
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff812cd91a)
Location: fs/ext4/ext4_jbd2.h:430
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/super.c (ffffffff812e7971)
Location: fs/ext4/ext4_jbd2.h:430
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/extents.c (ffffffff812f9c2f)
Location: fs/ext4/ext4_jbd2.h:430
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812fb52f)
Location: fs/ext4/ext4_jbd2.h:430
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/move_extent.c (ffffffff813070ef)
Location: fs/ext4/ext4_jbd2.h:430
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/indirect.c (ffffffff813087eb)
Location: fs/ext4/ext4_jbd2.h:430
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff81310b52)
Location: fs/ext4/ext4_jbd2.h:430
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
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
In fs/ext4/file.c (ffffffff812d5455)
Location: fs/ext4/ext4_jbd2.h:432
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff812d57bd)
Location: fs/ext4/ext4_jbd2.h:432
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff812e36ea)
Location: fs/ext4/ext4_jbd2.h:432
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/super.c (ffffffff812fd6a1)
Location: fs/ext4/ext4_jbd2.h:432
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/extents.c (ffffffff8130fbff)
Location: fs/ext4/ext4_jbd2.h:432
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813114cf)
Location: fs/ext4/ext4_jbd2.h:432
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/move_extent.c (ffffffff8131d09f)
Location: fs/ext4/ext4_jbd2.h:432
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/indirect.c (ffffffff8131e7db)
Location: fs/ext4/ext4_jbd2.h:432
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff813269cb)
Location: fs/ext4/ext4_jbd2.h:432
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
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
In fs/ext4/ext4_jbd2.c (ffffffff812e63fc)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff812ee1c5)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff812f1db4)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff812f3481)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff812f733c)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff812faa43)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81307cc1)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff81315b2f)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff8133233e)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffff8130ae0e)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81312c85)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff81316253)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff81317a18)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff8131b97c)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8131f09c)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8132c911)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff8133a385)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff81356831)
Location: fs/ext4/ext4_jbd2.h:428
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffff81338d13)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81340b50)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/file.c (ffffffff813441d5)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff8134590c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff8134994c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8134cd12)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8135ab41)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff8136893b)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff81384b41)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffff8134ffc3)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81358160)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/file.c (ffffffff8135c33a)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff8135da17)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff81361b0c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff81364e52)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81372e01)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff81380dcc)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff8139d631)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffff81378c63)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff813816c0)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff81385461)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff81386bc5)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff8138af0b)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8138d72c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8139c25e)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff813aa0d9)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813c7884)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffff81391023)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81399c70)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff8139df91)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff8139f615)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff813a395b)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff813a618c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813b4d6e)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff813c3009)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813e0c44)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffff813dc8f0)
Location: fs/ext4/ext4_jbd2.h:465
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff813e33ca)
Location: fs/ext4/ext4_jbd2.h:465
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff813e96da)
Location: fs/ext4/ext4_jbd2.h:465
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff813eb509)
Location: fs/ext4/ext4_jbd2.h:465
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff813efafd)
Location: fs/ext4/ext4_jbd2.h:465
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff813f2c48)
Location: fs/ext4/ext4_jbd2.h:465
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81400209)
Location: fs/ext4/ext4_jbd2.h:465
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff8140f60b)
Location: fs/ext4/ext4_jbd2.h:465
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff8142d81a)
Location: fs/ext4/ext4_jbd2.h:465
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffff813ee33b)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff813f4bd9)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff813fb38a)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff813fd6c4)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff8140225d)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff81405398)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814129f3)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff81422acb)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff814464c8)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_journal_finish_inode_data_buffers
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
```
In fs/ext4/fast_commit.c (ffffffff81456ff3)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
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
In fs/ext4/ext4_jbd2.c (ffffffff813f48fb)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff813faf19)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff8140185a)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81403ad4)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff8140865d)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8140b6d6)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81418e53)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff814292cb)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff8144bc7f)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_journal_finish_inode_data_buffers
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
```
In fs/ext4/fast_commit.c (ffffffff8145c9a3)
Location: fs/ext4/ext4_jbd2.h:457
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
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
In fs/ext4/ext4_jbd2.c (ffffffff81446adb)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff8144d2fc)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff81453dea)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff814562a4)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff8145b0bd)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8145e35b)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8146c087)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff8147d0cd)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff8149fc92)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_journal_finish_inode_data_buffers
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
```
In fs/ext4/fast_commit.c (ffffffff814b01f3)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
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
In fs/ext4/ext4_jbd2.c (ffffffff814c2d7f)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff814c9d8a)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff814d177c)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_supported
```
```
In fs/ext4/fsync.c (ffffffff814d3d4c)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff814d8e63)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff814dc6a9)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814ec07a)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff814ff943)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff815268ac)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_journal_finish_inode_data_buffers
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
```
In fs/ext4/fast_commit.c (ffffffff81538877)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
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
In fs/ext4/ext4_jbd2.c (ffffffff8155b0ef)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81562415)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/fsync.c (ffffffff8156c99c)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff81571c83)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8157566d)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81585de4)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff8159a123)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff815c417c)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_journal_finish_inode_data_buffers
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
```
In fs/ext4/fast_commit.c (ffffffff815d6b74)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
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
In fs/ext4/ext4_jbd2.c (ffffffff81592f0b)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff815962fa)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/indirect.c (ffffffff815a9a13)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff815ad1cc)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815bc6cc)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff815d09b9)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff815f5a05)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_finish_inode_data_buffers
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
```
In fs/ext4/fast_commit.c (ffffffff8160e744)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
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
In fs/ext4/ext4_jbd2.c (ffffffff815cbbfb)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff815cefa6)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/indirect.c (ffffffff815e27b3)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff815e5f7c)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815f54a9)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff816091f5)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff8162e315)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_finish_inode_data_buffers
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
```
In fs/ext4/fast_commit.c (ffffffff81647504)
Location: fs/ext4/ext4_jbd2.h:463
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
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
In fs/ext4/ext4_jbd2.c (ffff800010463b28)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffff80001046c670)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffff8000104714ec)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffff800010472a54)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffff800010476fd0)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffff800010479820)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffff800010489514)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffff80001049a8e0)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffff8000104b9fcc)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (c062414c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (c062da44)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (c0632318)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (c0633e14)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (c0638ad4)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (c063b30c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (c064b9d8)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (c065c24c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (c067d644)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (c000000000580d5c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (c00000000058c034)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (c000000000591dc8)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (c000000000593814)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (c000000000599060)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (c00000000059c90c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (c0000000005b0538)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (c0000000005c5104)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (c0000000005ef600)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffe0002f2334)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffe0002f9b80)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffe0002fd756)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffe0002fe85c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffe0003022c0)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffe00030499c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffe000310db4)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffe00031e014)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffe000336550)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffff81389603)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81392250)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff81396571)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff81397bf5)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff8139bf3b)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8139e76c)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813ad34e)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff813bb5e9)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813d9224)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffff8137a093)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81382ce0)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff81387001)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff81388685)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff8138c9cb)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8138f1fc)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8139ddde)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff813ac079)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813c9ca4)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffff81386f63)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff8138fbb0)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff81393ed1)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff81395555)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff8139979b)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8139bfcc)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813aabae)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff813b8e49)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813d66b4)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
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
In fs/ext4/ext4_jbd2.c (ffffffff8139ac3e)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff813a39f0)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff813a7f61)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff813a9689)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/indirect.c (ffffffff813ad88b)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff813b04ec)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813bf4fe)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/move_extent.c (ffffffff813cdb69)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff813eb964)
Location: fs/ext4/ext4_jbd2.h:425
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
```
</details>
</li>
</ul>

## Differences
