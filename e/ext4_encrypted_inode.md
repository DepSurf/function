# Function: <code>ext4_encrypted_inode</code>

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
In fs/ext4/dir.c (ffffffff81290995)
Location: fs/ext4/ext4.h:1536
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff812919e7)
Location: fs/ext4/ext4.h:1536
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
```
```
In fs/ext4/ialloc.c (ffffffff812942a3)
Location: fs/ext4/ext4.h:1536
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812979fd)
Location: fs/ext4/ext4.h:1536
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/page-io.c (ffffffff8129ff1a)
Location: fs/ext4/ext4.h:1536
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/ioctl.c (ffffffff812a07ad)
Location: fs/ext4/ext4.h:1536
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812a274a)
Location: fs/ext4/ext4.h:1536
Inline: True
Inline callers:
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_link
```
```
In fs/ext4/extents.c (ffffffff812c272d)
Location: fs/ext4/ext4.h:1536
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/readpage.c (ffffffff812e32a5)
Location: fs/ext4/ext4.h:1536
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/crypto_policy.c (ffffffff812e4b67)
Location: fs/ext4/ext4.h:1536
Inline: True
Inline callers:
  - fs/ext4/crypto_policy.c:ext4_is_child_context_consistent_with_parent
  - fs/ext4/crypto_policy.c:ext4_is_child_context_consistent_with_parent
```
```
In fs/ext4/crypto_fname.c (ffffffff812e683d)
Location: fs/ext4/ext4.h:1536
Inline: True
Inline callers:
  - fs/ext4/crypto_fname.c:ext4_fname_setup_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool ext4_encrypted_inode(struct inode *inode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812be587)
Location: fs/ext4/ext4.h:2295
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff812bef56)
Location: fs/ext4/ext4.h:2295
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_open
```
```
In fs/ext4/ialloc.c (ffffffff812c183b)
Location: fs/ext4/ext4.h:2295
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812c857e)
Location: fs/ext4/ext4.h:2295
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812ce815)
Location: fs/ext4/ext4.h:2295
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/ioctl.c (ffffffff812cfa02)
Location: fs/ext4/ext4.h:2295
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812d3408)
Location: fs/ext4/ext4.h:2295
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
```
In fs/ext4/super.c (ffffffff812d7f80)
Location: fs/ext4/ext4.h:2295
Inline: False
```
```
In fs/ext4/extents.c (ffffffff812fa0ba)
Location: fs/ext4/ext4.h:2295
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
```
In fs/ext4/readpage.c (ffffffff81312fdd)
Location: fs/ext4/ext4.h:2295
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff812d7f80-ffffffff812d7f94: ext4_encrypted_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool ext4_encrypted_inode(struct inode *inode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812d3be3)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff812d4576)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff812d57fe)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812d6e63)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812e3789)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/page-io.c (ffffffff812e45f5)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/namei.c (ffffffff812e9158)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
```
In fs/ext4/super.c (ffffffff812fd741)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/extents.c (ffffffff8130fde2)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81311561)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/mballoc.c (ffffffff8131ac6e)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8131d0d6)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/indirect.c (ffffffff8131e864)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff81326bd9)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/readpage.c (ffffffff81328f81)
Location: fs/ext4/ext4.h:2275
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff812edb60-ffffffff812edb74: ext4_encrypted_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool ext4_encrypted_inode(struct inode *inode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812e55b1)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812e6478)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff812ee2fc)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff812f0efb)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff812f3557)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812f518e)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff812f7471)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff812fab1a)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81307d07)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
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
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mballoc.c (ffffffff81312190)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81315b63)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff813188e8)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
```
In fs/ext4/page-io.c (ffffffff8131e2d9)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8131ed00)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff81332467)
Location: fs/ext4/ext4.h:2311
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
```
**Symbols:**

```
ffffffff81322b70-ffffffff81322b84: ext4_encrypted_inode (STB_LOCAL)
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
In fs/ext4/dir.c (ffffffff81309fd9)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8130ae8a)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81312dbf)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff8131646e)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff81317af1)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813198e8)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8131bab1)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8131f1fd)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8132c957)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
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
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mballoc.c (ffffffff8133697f)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8133a3c3)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff813417bb)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
```
In fs/ext4/page-io.c (ffffffff813428f9)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8134336b)
Location: fs/ext4/ext4.h:2271
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff81356974)
Location: fs/ext4/ext4.h:2271
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
In fs/ext4/dir.c (ffffffff81337ef2)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81338d46)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81340c86)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/file.c (ffffffff81344304)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff813459a9)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81347653)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8134999e)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff8134d114)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8135af62)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
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
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mballoc.c (ffffffff81364f1b)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8136896b)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff81369cdd)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
```
In fs/ext4/page-io.c (ffffffff8137078e)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81371143)
Location: fs/ext4/ext4.h:2272
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff81384bea)
Location: fs/ext4/ext4.h:2272
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
In fs/ext4/dir.c (ffffffff8134f183)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8134fff6)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81358296)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/file.c (ffffffff8135c45b)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (ffffffff8135db1a)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8135f803)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff81361b5e)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/inline.c (ffffffff81365237)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81373222)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
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
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mballoc.c (ffffffff8137d2d6)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81380dfc)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff8138219d)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
```
In fs/ext4/page-io.c (ffffffff81388c1a)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813895e5)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff8139d6da)
Location: fs/ext4/ext4.h:2285
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
