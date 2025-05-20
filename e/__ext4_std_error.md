# Function: <code>__ext4_std_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b8800)
Location: fs/ext4/super.c:538
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
```
**Symbols:**

```
ffffffff812b8800-ffffffff812b88e7: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e7690)
Location: fs/ext4/super.c:567
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff812e7690-ffffffff812e7777: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fd300)
Location: fs/ext4/super.c:569
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff812fd300-ffffffff812fd3e7: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81331f80)
Location: fs/ext4/super.c:583
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81331f80-ffffffff8133206f: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81356470)
Location: fs/ext4/super.c:583
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81356470-ffffffff8135655f: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813847a0)
Location: fs/ext4/super.c:589
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813847a0-ffffffff81384889: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8139d280)
Location: fs/ext4/super.c:631
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8139d280-ffffffff8139d369: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c74b0)
Location: fs/ext4/super.c:642
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813c74b0-ffffffff813c759e: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e0870)
Location: fs/ext4/super.c:637
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813e0870-ffffffff813e095e: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142d5e0)
Location: fs/ext4/super.c:672
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8142d5e0-ffffffff8142d6e8: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81446350)
Location: fs/ext4/super.c:869
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81446350-ffffffff81446430: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144bb00)
Location: fs/ext4/super.c:878
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_orphan_cleanup
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8144bb00-ffffffff8144bbe0: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149fb00)
Location: fs/ext4/super.c:877
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff8149fb00-ffffffff8149fbe0: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81526330)
Location: fs/ext4/super.c:902
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff81526330-ffffffff815264a7: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c3bf0)
Location: fs/ext4/super.c:895
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff815c3bf0-ffffffff815c3d6e: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fb340)
Location: fs/ext4/super.c:895
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff815fb340-ffffffff815fb4be: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81633f20)
Location: fs/ext4/super.c:964
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_insert_index
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/orphan.c:ext4_process_orphan
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff81633f20-ffffffff8163409e: __ext4_std_error (STB_GLOBAL)
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
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b9bb0)
Location: fs/ext4/super.c:637
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffff8000104b9bb0-ffff8000104b9cac: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067d21c)
Location: fs/ext4/super.c:637
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
c067d21c-c067d330: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005ef0a0)
Location: fs/ext4/super.c:637
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
c0000000005ef0a0-c0000000005ef1fc: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe0003361e2)
Location: fs/ext4/super.c:637
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffe0003361e2-ffffffe00033629c: __ext4_std_error (STB_GLOBAL)
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
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8e50)
Location: fs/ext4/super.c:637
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813d8e50-ffffffff813d8f3e: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c98d0)
Location: fs/ext4/super.c:637
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813c98d0-ffffffff813c99be: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d62e0)
Location: fs/ext4/super.c:637
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813d62e0-ffffffff813d63ce: __ext4_std_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __ext4_std_error(struct super_block *sb, const char *function, unsigned int line, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813eb590)
Location: fs/ext4/super.c:637
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_append
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813eb590-ffffffff813eb67e: __ext4_std_error (STB_GLOBAL)
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
