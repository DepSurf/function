# Function: <code>ext4_test_inode_flag</code>

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
In fs/ext4/dir.c (ffffffff81290950)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff81291935)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_llseek
```
```
In fs/ext4/fsync.c (ffffffff81292db2)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81293336)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81295e53)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_getattr
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/ext4/page-io.c (ffffffff8129ff1a)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/ioctl.c (ffffffff812a07ad)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812a1a57)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_link
```
```
In fs/ext4/super.c (ffffffff812b8b5c)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/extents.c (ffffffff812c272d)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812cbc25)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/migrate.c (ffffffff812cc641)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/mballoc.c (ffffffff812cd76a)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/move_extent.c (ffffffff812d73c0)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/indirect.c (ffffffff812d8a7c)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_direct_IO
  - fs/ext4/indirect.c:ext4_ind_direct_IO
```
```
In fs/ext4/xattr.c (ffffffff812dd968)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/inline.c (ffffffff812e0470)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
```
```
In fs/ext4/readpage.c (ffffffff812e32a5)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/acl.c (ffffffff812e44d4)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/crypto_policy.c (ffffffff812e4910)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/crypto_policy.c:ext4_process_policy
  - fs/ext4/crypto_policy.c:ext4_is_child_context_consistent_with_parent
  - fs/ext4/crypto_policy.c:ext4_is_child_context_consistent_with_parent
```
```
In fs/ext4/crypto_fname.c (ffffffff812e683d)
Location: fs/ext4/ext4.h:1504
Inline: True
Inline callers:
  - fs/ext4/crypto_fname.c:ext4_fname_setup_filename
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
In fs/ext4/dir.c (ffffffff812be587)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff812bfc76)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff812c02a5)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812c183b)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff812cd9c2)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/page-io.c (ffffffff812ce815)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/ioctl.c (ffffffff812cfa02)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812d3408)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff812e79f0)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_encrypted_inode
```
```
In fs/ext4/extents.c (ffffffff812f9bda)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812fb54a)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/migrate.c (ffffffff812fc6d4)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mballoc.c (ffffffff81304c86)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/move_extent.c (ffffffff81307110)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/indirect.c (ffffffff81308821)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130e6f5)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff81312b46)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff81312fdd)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/acl.c (ffffffff813143eb)
Location: fs/ext4/ext4.h:1581
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/dir.c (ffffffff812d3be3)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/file.c (ffffffff812d4e86)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff812d57fe)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812d6e63)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff812e3789)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/page-io.c (ffffffff812e45f5)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/namei.c (ffffffff812e9158)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff812fd726)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/extents.c (ffffffff8130fbaa)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81311561)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/migrate.c (ffffffff81312684)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mballoc.c (ffffffff8131ac42)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/move_extent.c (ffffffff8131d0bc)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/indirect.c (ffffffff8131e80d)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff81324435)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff81328ac8)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff81328f81)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/acl.c (ffffffff8132a3cb)
Location: fs/ext4/ext4.h:1586
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/dir.c (ffffffff812e55b1)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812e6478)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff812ee16b)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff812f1795)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff812f3557)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812f518e)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff812f71a3)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff812fcaa8)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81307cae)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mballoc.c (ffffffff81312109)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff81314164)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81315b4c)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff813188e8)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/page-io.c (ffffffff8131e2d9)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8131ed00)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff81332454)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffffffff8133da14)
Location: fs/ext4/ext4.h:1591
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8130ae8a)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81312c2b)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff81315941)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff81317af1)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813198e8)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff8131b7e3)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81321308)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8132c8fe)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mballoc.c (ffffffff8133692f)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff81338924)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8133a3ac)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff8133d128)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/page-io.c (ffffffff813428f9)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8134336b)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff81356961)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffffffff81361ff4)
Location: fs/ext4/ext4.h:1551
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81338d2a)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81340aea)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/file.c (ffffffff81343752)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff813459a9)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81347653)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff81349717)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8134f318)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8135af62)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mballoc.c (ffffffff81364c62)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff81366e44)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81368958)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff8136b6e4)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/page-io.c (ffffffff8137078e)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81371143)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff81384bcf)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffffffff8138f2d4)
Location: fs/ext4/ext4.h:1554
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8134ffda)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff813580fa)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/file.c (ffffffff8135b892)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff8135db1a)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8135f803)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff813618d7)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813674c8)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81373222)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81374757)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff8137cf66)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff8137f2b3)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81380de9)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff81383ba4)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/page-io.c (ffffffff81388c1a)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813895e5)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff8139d6bf)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffffffff813a7d20)
Location: fs/ext4/ext4.h:1567
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff81377f55)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81378c7a)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff8138165a)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff81384922)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
```
```
In fs/ext4/fsync.c (ffffffff81386d41)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81388a93)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff8138ac99)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81390898)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8139c4e0)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8139d245)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813a6bcd)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff813a8733)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813aa0fd)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff813ad364)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813c7914)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffffffff813d20df)
Location: fs/ext4/ext4.h:1584
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff813902f5)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8139103a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81399c0a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff8139d3a2)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
```
```
In fs/ext4/fsync.c (ffffffff8139f791)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813a1405)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff813a36e9)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813a92f8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813b4ff0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813b5cb5)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813bfa50)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff813c1629)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813c302d)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff813c62a4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813e0cd4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffffffff813eb7bf)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (ffffffff813ef0cc)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (ffffffff813db8dd)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813dc3e6)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
```
```
In fs/ext4/extents.c (ffffffff813e337a)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap_check_ranges
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/file.c (ffffffff813e95d2)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/ialloc.c (ffffffff813ed6e6)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff813efb85)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813f5229)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81400558)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:ext4_set_iomap
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81401695)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81408a60)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff8140d909)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8140e725)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
```
```
In fs/ext4/namei.c (ffffffff8141273b)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8142770c)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff81438d51)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (ffffffff8143bd6e)
Location: fs/ext4/ext4.h:1724
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (ffffffff813ed322)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813ede86)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
```
```
In fs/ext4/extents.c (ffffffff813f4b8f)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap_check_ranges
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/file.c (ffffffff813fb282)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/ialloc.c (ffffffff813ffe2d)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff814022e5)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff814079c9)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81412e94)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:ext4_set_iomap
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81414085)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff8141c297)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff81420d69)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81421bd5)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
```
```
In fs/ext4/namei.c (ffffffff81425bdb)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8143f50e)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff8145187a)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (ffffffff814580ce)
Location: fs/ext4/ext4.h:1841
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (ffffffff813f3985)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813f43b6)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
```
```
In fs/ext4/extents.c (ffffffff813faecf)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap_check_ranges
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/file.c (ffffffff81401752)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/ialloc.c (ffffffff814061df)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff814086e5)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8140de39)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814192f4)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_set_iomap
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8141a2f4)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81422820)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff8142751f)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff814283db)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
```
```
In fs/ext4/namei.c (ffffffff8142c7e4)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8144a575)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff81456faa)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (ffffffff8145dc2e)
Location: fs/ext4/ext4.h:1850
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (ffffffff81445a48)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff814464f6)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
```
```
In fs/ext4/extents.c (ffffffff8144d29d)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap_check_ranges
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/file.c (ffffffff81453ce2)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/ialloc.c (ffffffff81458a3f)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff8145b145)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81460cf9)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8146c53a)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_set_iomap
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8146d4e8)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81475f86)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff8147b19f)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8147c09a)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
```
```
In fs/ext4/namei.c (ffffffff814806e4)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8149e03b)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff814ab00f)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (ffffffff814b30ee)
Location: fs/ext4/ext4.h:1912
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (ffffffff814c1a8c)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff814c268e)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
```
```
In fs/ext4/extents.c (ffffffff814cda04)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/file.c (ffffffff814d0ce2)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/file.c:ext4_dio_supported
```
```
In fs/ext4/ialloc.c (ffffffff814d6607)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff814d8e18)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff814df6e7)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814ec58f)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_set_iomap
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/ioctl.c (ffffffff814eddaa)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff814f829f)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff814fd601)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff814fe5d9)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
```
```
In fs/ext4/namei.c (ffffffff81503614)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8152263b)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/symlink.c (ffffffff8152e9c5)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff81532fb7)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/fast_commit.c (ffffffff81535c9b)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
```
In fs/ext4/verity.c (ffffffff8153bade)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8153c834)
Location: fs/ext4/ext4.h:1914
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
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
In fs/ext4/dir.c (ffffffff81559d43)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8155a91e)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
```
```
In fs/ext4/extents.c (ffffffff81566164)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/file.c (ffffffff81569702)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/ialloc.c (ffffffff8156f3c1)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff81571c38)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81578827)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff815862fa)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_set_iomap
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/ioctl.c (ffffffff81587c71)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81592581)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff81597dd1)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81598e19)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
```
```
In fs/ext4/namei.c (ffffffff8159e167)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff815bf45b)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/symlink.c (ffffffff815ccb25)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff815d232a)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/fast_commit.c (ffffffff815d415b)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
```
In fs/ext4/verity.c (ffffffff815da15e)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff815dafa4)
Location: fs/ext4/ext4.h:1924
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
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
In fs/ext4/dir.c (ffffffff81591b6a)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8159273e)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
```
```
In fs/ext4/extents.c (ffffffff8159ddf4)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/file.c (ffffffff815a1472)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/ialloc.c (ffffffff815a7200)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff815a99c8)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff815afdc7)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815bca50)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_set_iomap
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/ioctl.c (ffffffff815be4f1)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff815c9542)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff815ce843)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff815cf8f9)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
```
```
In fs/ext4/namei.c (ffffffff815d4a77)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff815f661b)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/symlink.c (ffffffff81604615)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff8160b016)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/fast_commit.c (ffffffff8160bd3c)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
```
In fs/ext4/verity.c (ffffffff81611ea1)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff81612a54)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
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
In fs/ext4/dir.c (ffffffff815ca8da)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815cb45e)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
  - fs/ext4/ext4_jbd2.c:ext4_inode_journal_mode
```
```
In fs/ext4/extents.c (ffffffff815d6a44)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/file.c (ffffffff815da232)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/ialloc.c (ffffffff815e0052)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff815e2768)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff815e8b77)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815f5831)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_set_iomap
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/ioctl.c (ffffffff815f72aa)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81602321)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff816070c3)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81608189)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
```
```
In fs/ext4/namei.c (ffffffff8160d125)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff8162ef1b)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/symlink.c (ffffffff8163d2e5)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff81643dd6)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/fast_commit.c (ffffffff81644afc)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
```
In fs/ext4/verity.c (ffffffff8164ac41)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8164b7d4)
Location: fs/ext4/ext4.h:1936
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
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
In fs/ext4/dir.c (ffff800010462c00)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffff800010463b40)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffff80001046c628)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffff800010470870)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
```
```
In fs/ext4/fsync.c (ffff800010472c2c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffff800010474c44)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffff800010476d7c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffff80001047cbc4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffff8000104897a8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffff80001048a6b8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffff8000104966b8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffff800010498aec)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffff80001049a8fc)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffff80001049ddb0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffff8000104ba054)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffff8000104c4774)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (ffff8000104c83f8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (c0622e20)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (c0624168)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (c062d9e0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (c0631e80)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/fsync.c (c06340b4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (c0636240)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (c0638880)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c063e69c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c064bcf4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (c064c928)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (c0658218)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (c065a6e8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (c065c26c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (c065fa94)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (c067d6c8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (c06886f4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (c068c34c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (c00000000057f55c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (c000000000580d80)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (c00000000058bfc0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (c000000000590c54)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (c000000000593c20)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (c00000000059642c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (c000000000598d3c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c0000000005a0718)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c0000000005b097c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (c0000000005b1a68)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (c0000000005c0770)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (c0000000005c2e78)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (c0000000005c5124)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (c0000000005c9654)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (c0000000005ef6c0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (c0000000005fc048)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (c0000000006010f8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (ffffffe0002f15c4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffe0002f2348)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffe0002f9b3c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffe0002fcc88)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
```
```
In fs/ext4/fsync.c (ffffffe0002fea98)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffe00030068a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffe0003022b2)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffe000306a92)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffe000310da0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffe000311aa6)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffe00031af6e)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffe00031c9f0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffe00031e030)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffe000320918)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffe0003365d2)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffffffe00033f080)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (ffffffe0003422a4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (ffffffff813888d5)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8138961a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff813921ea)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff81395982)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
```
```
In fs/ext4/fsync.c (ffffffff81397d71)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813999e5)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff8139bcc9)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813a18d8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813ad5d0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813ae295)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813b8030)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff813b9c09)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813bb60d)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff813be884)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813d92b4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffffffff813e3d9f)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (ffffffff813e76ac)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (ffffffff81379365)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8137a0aa)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff81382c7a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff81386412)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
```
```
In fs/ext4/fsync.c (ffffffff81388801)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8138a475)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff8138c759)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81392368)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8139e060)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8139ed25)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813a8ac0)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff813aa699)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813ac09d)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff813af314)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813c9d34)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffffffff813d481f)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (ffffffff813d812c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (ffffffff81386235)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81386f7a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff8138fb4a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff813932e2)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
```
```
In fs/ext4/fsync.c (ffffffff813956d1)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81397245)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff81399529)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8139f138)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813aae30)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813abaf5)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813b5890)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff813b7469)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813b8e6d)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff813bbe64)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813d6744)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffffffff813e111f)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (ffffffff813e4a2c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/dir.c (ffffffff81399f25)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8139ac57)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/extents.c (ffffffff813a398a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
```
In fs/ext4/file.c (ffffffff813a7372)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_write_checks
```
```
In fs/ext4/fsync.c (ffffffff813a981e)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813ab56c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/indirect.c (ffffffff813ad619)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813b36a8)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813bf77b)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_meta_trans_blocks
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813c0495)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813ca529)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/migrate.c (ffffffff813cc179)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813cdb8d)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff813d0e14)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff813eb9f4)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/xattr.c (ffffffff813f653a)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
```
In fs/ext4/verity.c (ffffffff813f9e7c)
Location: fs/ext4/ext4.h:1629
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
</details>
</li>
</ul>

## Differences
