# Function: <code>__ext4_error_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b84e0)
Location: fs/ext4/super.c:428
Inline: False
Direct callers:
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/crypto_policy.c:ext4_process_policy
  - fs/ext4/crypto_fname.c:_ext4_fname_disk_to_usr
```
**Symbols:**

```
ffffffff812b84e0-ffffffff812b864d: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e71e0)
Location: fs/ext4/super.c:457
Inline: False
Direct callers:
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/inline.c:empty_inline_dir
```
**Symbols:**

```
ffffffff812e71e0-ffffffff812e734d: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fcdc0)
Location: fs/ext4/super.c:459
Inline: False
Direct callers:
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/inline.c:empty_inline_dir
```
**Symbols:**

```
ffffffff812fcdc0-ffffffff812fcf2d: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81331a40)
Location: fs/ext4/super.c:467
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:__xattr_check_inode
```
**Symbols:**

```
ffffffff81331a40-ffffffff81331bc1: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81355ef0)
Location: fs/ext4/super.c:467
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:__xattr_check_inode
```
**Symbols:**

```
ffffffff81355ef0-ffffffff8135608c: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:471
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
```
**Symbols:**

```
ffffffff8138b910-ffffffff8138b9d3: __ext4_error_inode.cold.136 (STB_LOCAL)
ffffffff813842c0-ffffffff81384413: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:513
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
```
**Symbols:**

```
ffffffff813a4470-ffffffff813a4533: __ext4_error_inode.cold.140 (STB_LOCAL)
ffffffff8139cda0-ffffffff8139cef3: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:524
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
```
**Symbols:**

```
ffffffff813ce692-ffffffff813ce73a: __ext4_error_inode.cold (STB_LOCAL)
ffffffff813c6fd0-ffffffff813c711f: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:519
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff813e7d51-ffffffff813e7df9: __ext4_error_inode.cold (STB_LOCAL)
ffffffff813e0390-ffffffff813e04df: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, int error, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:558
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_dx_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_block_list
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
```
**Symbols:**

```
ffffffff81434818-ffffffff814348c0: __ext4_error_inode.cold (STB_LOCAL)
ffffffff8142d0b0-ffffffff8142d1f9: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, int error, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:757
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_dx_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_block_list
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
```
**Symbols:**

```
ffffffff81bec6b6-ffffffff81bec755: __ext4_error_inode.cold (STB_LOCAL)
ffffffff81445ed0-ffffffff81445fcb: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, int error, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:766
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
```
**Symbols:**

```
ffffffff81bde768-ffffffff81bde807: __ext4_error_inode.cold (STB_LOCAL)
ffffffff8144b680-ffffffff8144b77a: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, int error, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:765
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc_noinmem
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
```
**Symbols:**

```
ffffffff81ccd8a8-ffffffff81ccd947: __ext4_error_inode.cold (STB_LOCAL)
ffffffff8149f680-ffffffff8149f777: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, int error, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:786
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc_noinmem
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff81e80781-ffffffff81e8081c: __ext4_error_inode.cold (STB_LOCAL)
ffffffff81525f90-ffffffff8152613a: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, int error, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c36d0)
Location: fs/ext4/super.c:779
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc_noinmem
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
  - fs/ext4/xattr.c:__ext4_xattr_check_block
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff815c36d0-ffffffff815c3920: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, int error, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fae20)
Location: fs/ext4/super.c:779
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc_noinmem
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:check_xattrs
  - fs/ext4/xattr.c:check_xattrs
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff815fae20-ffffffff815fb070: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, int error, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81633a00)
Location: fs/ext4/super.c:848
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_search_left
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
  - fs/ext4/inline.c:get_max_inline_xattr_value_size
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc_noinmem
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_handle_dirty_dx_node
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:check_xattrs
  - fs/ext4/xattr.c:check_xattrs
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff81633a00-ffffffff81633c50: __ext4_error_inode (STB_GLOBAL)
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
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b9520)
Location: fs/ext4/super.c:519
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffff8000104b9520-ffff8000104b9700: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067cbb4)
Location: fs/ext4/super.c:519
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
c067cbb4-c067cdbc: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005ee850)
Location: fs/ext4/super.c:519
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
c0000000005ee850-c0000000005eea8c: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000335d0e)
Location: fs/ext4/super.c:519
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffe000335d0e-ffffffe000335e7c: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:519
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff813e0331-ffffffff813e03d9: __ext4_error_inode.cold (STB_LOCAL)
ffffffff813d8970-ffffffff813d8abf: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:519
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff813d0db1-ffffffff813d0e59: __ext4_error_inode.cold (STB_LOCAL)
ffffffff813c93f0-ffffffff813c953f: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:519
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff813dd6b1-ffffffff813dd759: __ext4_error_inode.cold (STB_LOCAL)
ffffffff813d5e00-ffffffff813d5f4f: __ext4_error_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __ext4_error_inode(struct inode *inode, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:519
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:__ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:xattr_find_entry
  - fs/ext4/xattr.c:__xattr_check_inode
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff813f2ae1-ffffffff813f2b85: __ext4_error_inode.cold (STB_LOCAL)
ffffffff813eb080-ffffffff813eb1ec: __ext4_error_inode (STB_GLOBAL)
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
<b>Param added. </b>
<code>int error</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, function, line, block, fmt, (anon)</code> ➡️ <code>inode, function, line, block, error, fmt, (anon)</code>
</li>
</ul>
</details>
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
