# Function: <code>ext4_free_metadata_revoke_credits</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e3525)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
```
In fs/ext4/file.c (ffffffff813e8acb)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff813eed51)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff813efe51)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/inline.c (ffffffff813f52a5)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814003fa)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81402972)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff8140d944)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8140edce)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
```
```
In fs/ext4/namei.c (ffffffff814128c9)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/resize.c (ffffffff81419425)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff8142582f)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_write_info
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff8143ac68)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
```
In fs/ext4/acl.c (ffffffff8143b948)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff8143c154)
Location: fs/ext4/ext4_jbd2.h:295
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff813f4d2b)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
```
In fs/ext4/file.c (ffffffff813fb07c)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff814014cc)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff814025b1)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/inline.c (ffffffff81407a45)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81412b0e)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8141527c)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81420da4)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81422291)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81425d69)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/resize.c (ffffffff8142d4cf)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff8143d1af)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_write_info
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff814537d8)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
```
In fs/ext4/acl.c (ffffffff81457c77)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff8145853a)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff813fb06b)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
```
In fs/ext4/file.c (ffffffff8140154c)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff81407a11)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff814089b1)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/inline.c (ffffffff8140deb5)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81418f6e)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8141b2fd)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81427564)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81428aa1)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8142c96d)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/resize.c (ffffffff8143418f)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff81442fef)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_write_info
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff814590f8)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
```
In fs/ext4/acl.c (ffffffff8145d61f)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff8145dedc)
Location: fs/ext4/ext4_jbd2.h:287
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff8144d45a)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
```
In fs/ext4/file.c (ffffffff81453acc)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff8145a2b9)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8145b421)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/inline.c (ffffffff81460d75)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8146c1a2)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8146e606)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff8147b1e4)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8147c86a)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8148086d)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/resize.c (ffffffff81487be9)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff81496c9d)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_write_info
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff814ad208)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
```
In fs/ext4/acl.c (ffffffff814b2adf)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff814b33fb)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff814c9f39)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
```
```
In fs/ext4/file.c (ffffffff814d0faf)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff814d7fb4)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff814d91de)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/inline.c (ffffffff814df776)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814ec218)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff814eef7e)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/migrate.c (ffffffff814fd647)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff814fef5e)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
```
```
In fs/ext4/namei.c (ffffffff815037aa)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/resize.c (ffffffff8150b49a)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff81521c23)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_write_info
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/xattr.c (ffffffff815352a3)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
```
In fs/ext4/acl.c (ffffffff8153b705)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff8153bfe3)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8153c98a)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
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
In fs/ext4/extents.c (ffffffff815625c6)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
```
```
In fs/ext4/file.c (ffffffff815699ef)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff81570d34)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8157201e)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/inline.c (ffffffff815788b6)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81585f7e)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8158910b)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/migrate.c (ffffffff81597e17)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff815997d6)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8159e301)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/resize.c (ffffffff815a613b)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff815be71d)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_write_info
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/xattr.c (ffffffff815d36e3)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
```
In fs/ext4/acl.c (ffffffff815d9d2b)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff815da693)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff815db0fa)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
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
In fs/ext4/extents.c (ffffffff8159a308)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
```
```
In fs/ext4/file.c (ffffffff815a17df)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff815a8abd)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff815a9dae)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/inline.c (ffffffff815afe56)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815bc87d)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815bf933)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/migrate.c (ffffffff815ce8b5)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff815d00c9)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
```
```
In fs/ext4/namei.c (ffffffff815d4c11)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/resize.c (ffffffff815dc9ab)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff815f542d)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_write_info
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/xattr.c (ffffffff8160b293)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
```
In fs/ext4/acl.c (ffffffff8161190b)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff81612466)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff81612baa)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
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
In fs/ext4/extents.c (ffffffff815d3158)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
```
```
In fs/ext4/file.c (ffffffff815da58f)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff815e186a)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff815e2b4e)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/inline.c (ffffffff815e8c06)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815f565c)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f86d9)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/migrate.c (ffffffff81607135)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8160894f)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8160d2ba)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/resize.c (ffffffff8161528b)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff8162dd84)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_write_info
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/xattr.c (ffffffff81644053)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
```
In fs/ext4/acl.c (ffffffff8164a6be)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff8164b136)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8164b92a)
Location: fs/ext4/ext4_jbd2.h:293
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
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
