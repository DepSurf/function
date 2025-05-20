# Function: <code>__ext4_mark_inode_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t *handle, struct inode *inode, const char *func, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fbb10)
Location: fs/ext4/inode.c:5811
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:__ext4_ext_dirty
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_splice_branch
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff813fbb10-ffffffff813fbc47: __ext4_mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t *handle, struct inode *inode, const char *func, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140e250)
Location: fs/ext4/inode.c:5904
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:__ext4_ext_dirty
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_splice_branch
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_replay_del_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff8140e250-ffffffff8140e36e: __ext4_mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t *handle, struct inode *inode, const char *func, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81414410)
Location: fs/ext4/inode.c:5901
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:__ext4_ext_dirty
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff81414410-ffffffff81414600: __ext4_mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t *handle, struct inode *inode, const char *func, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81467790)
Location: fs/ext4/inode.c:5842
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:__ext4_ext_dirty
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff81467790-ffffffff81467980: __ext4_mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t *handle, struct inode *inode, const char *func, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e7400)
Location: fs/ext4/inode.c:5920
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:__ext4_ext_dirty
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff814e7400-ffffffff814e7639: __ext4_mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t *handle, struct inode *inode, const char *func, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81580dc0)
Location: fs/ext4/inode.c:6064
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:__ext4_ext_dirty
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff81580dc0-ffffffff81580ff9: __ext4_mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t *handle, struct inode *inode, const char *func, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b8370)
Location: fs/ext4/inode.c:5876
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:__ext4_ext_dirty
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff815b8370-ffffffff815b85a9: __ext4_mark_inode_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ext4_mark_inode_dirty(handle_t *handle, struct inode *inode, const char *func, unsigned int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815f1110)
Location: fs/ext4/inode.c:5896
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:__ext4_ext_dirty
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff815f1110-ffffffff815f1349: __ext4_mark_inode_dirty (STB_GLOBAL)
```
</details>
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
