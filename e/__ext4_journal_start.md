# Function: <code>__ext4_journal_start</code>

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
In fs/ext4/inode.c (ffffffff81299089)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/ext4/ioctl.c (ffffffff812a10a1)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812a4671)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_link
```
```
In fs/ext4/super.c (ffffffff812ac617)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_write_info
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/extents.c (ffffffff812c344c)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff812cc677)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff812d6865)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/indirect.c (ffffffff812d9df8)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_direct_IO
  - fs/ext4/indirect.c:ext4_ind_direct_IO
```
```
In fs/ext4/xattr.c (ffffffff812dea70)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/inline.c (ffffffff812e0ad8)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data
```
```
In fs/ext4/acl.c (ffffffff812e44ff)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/crypto_policy.c (ffffffff812e492c)
Location: fs/ext4/ext4_jbd2.h:306
Inline: True
Inline callers:
  - fs/ext4/crypto_policy.c:ext4_process_policy
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
In fs/ext4/inode.c (ffffffff812cdb58)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff812cfdb4)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/namei.c (ffffffff812d3634)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff812e0c37)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_write_info
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/extents.c (ffffffff812f9e3a)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/migrate.c (ffffffff812fc6fd)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813064f8)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/xattr.c (ffffffff8130e76c)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/inline.c (ffffffff81312baf)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/acl.c (ffffffff81314419)
Location: fs/ext4/ext4_jbd2.h:314
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
In fs/ext4/inode.c (ffffffff812e3934)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dirty_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff812e5ba9)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/namei.c (ffffffff812e9384)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff812f6773)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_write_info
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/extents.c (ffffffff8130fe1a)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/migrate.c (ffffffff813126ad)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8131c4b8)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/xattr.c (ffffffff813244ac)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/inline.c (ffffffff81328b33)
Location: fs/ext4/ext4_jbd2.h:314
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/acl.c (ffffffff8132a3f9)
Location: fs/ext4/ext4_jbd2.h:314
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
In fs/ext4/extents.c (ffffffff812ee3bc)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffffffff812fcb13)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81307a3d)
Location: fs/ext4/ext4_jbd2.h:310
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
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81309591)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff8131418d)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81315060)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff81318b72)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff8132b07e)
Location: fs/ext4/ext4_jbd2.h:310
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
In fs/ext4/xattr.c (ffffffff8133e165)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff8133f542)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/extents.c (ffffffff81312e85)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffffffff81321373)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8132c68d)
Location: fs/ext4/ext4_jbd2.h:310
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
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8132e15e)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff8133894d)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81339823)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff8133d306)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff8134f4ee)
Location: fs/ext4/ext4_jbd2.h:310
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
In fs/ext4/xattr.c (ffffffff81362745)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff81363b52)
Location: fs/ext4/ext4_jbd2.h:310
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/extents.c (ffffffff81340d2e)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffffffff8134f383)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8135ac63)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8135c7be)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff81366e6d)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81367d8c)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff8136b8ae)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff8137d958)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (ffffffff81390ed5)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff813922dd)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/extents.c (ffffffff8135833e)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffffffff81367533)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81372f23)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81374cc2)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/migrate.c (ffffffff8137f2e1)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8138020d)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff81383d6e)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff81396158)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (ffffffff813a9ad5)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff813aaf1d)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/extents.c (ffffffff81381880)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffffffff81390903)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8139c385)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8139e3a3)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813a8764)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813a992b)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813ad530)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff813c010b)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (ffffffff813d4055)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff813d513f)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/extents.c (ffffffff81399e30)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffffffff813a9363)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813b4e95)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813b7138)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813c165f)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813c285b)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813c6464)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff813d93db)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (ffffffff813ed735)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff813ee80f)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff813ef3a1)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff813e3525)
Location: fs/ext4/ext4_jbd2.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff813e91ee)
Location: fs/ext4/ext4_jbd2.h:323
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff813f52a5)
Location: fs/ext4/ext4_jbd2.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8140041a)
Location: fs/ext4/ext4_jbd2.h:323
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
Location: fs/ext4/ext4_jbd2.h:323
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff8140d944)
Location: fs/ext4/ext4_jbd2.h:323
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8140edce)
Location: fs/ext4/ext4_jbd2.h:323
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81412907)
Location: fs/ext4/ext4_jbd2.h:323
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff8142582f)
Location: fs/ext4/ext4_jbd2.h:323
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
In fs/ext4/xattr.c (ffffffff8143a7ad)
Location: fs/ext4/ext4_jbd2.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff8143b948)
Location: fs/ext4/ext4_jbd2.h:323
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff8143c154)
Location: fs/ext4/ext4_jbd2.h:323
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
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff813fb5ee)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff81407a45)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81412b2c)
Location: fs/ext4/ext4_jbd2.h:315
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
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81420da4)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81422291)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81425dab)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff8143d1af)
Location: fs/ext4/ext4_jbd2.h:315
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
In fs/ext4/xattr.c (ffffffff8145331d)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff81457c77)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff8145853a)
Location: fs/ext4/ext4_jbd2.h:315
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
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff81401abe)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff8140deb5)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81418f8c)
Location: fs/ext4/ext4_jbd2.h:315
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
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81427564)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81428aa1)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8142c9a1)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff81442fef)
Location: fs/ext4/ext4_jbd2.h:315
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
In fs/ext4/xattr.c (ffffffff81458b7d)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff8145d61f)
Location: fs/ext4/ext4_jbd2.h:315
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff8145dedc)
Location: fs/ext4/ext4_jbd2.h:315
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
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff8145404e)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff81460d75)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8146c1c0)
Location: fs/ext4/ext4_jbd2.h:321
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
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff8147b1e4)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8147c86a)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
```
```
In fs/ext4/namei.c (ffffffff814808a1)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff81496c9d)
Location: fs/ext4/ext4_jbd2.h:321
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
In fs/ext4/xattr.c (ffffffff814acc8d)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff814b2adf)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff814b33fb)
Location: fs/ext4/ext4_jbd2.h:321
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
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff814d15ce)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff814df776)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814ec236)
Location: fs/ext4/ext4_jbd2.h:321
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
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff814fd647)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff814fef5e)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
```
```
In fs/ext4/namei.c (ffffffff815037e0)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/super.c (ffffffff81521c23)
Location: fs/ext4/ext4_jbd2.h:321
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
In fs/ext4/xattr.c (ffffffff81534c64)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff8153b705)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff8153bfe3)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8153c98a)
Location: fs/ext4/ext4_jbd2.h:321
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
In fs/ext4/extents.c (ffffffff815625c6)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff8156a3d9)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815788b6)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81585f9b)
Location: fs/ext4/ext4_jbd2.h:321
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
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81597e17)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff815997d6)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8159e338)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/super.c (ffffffff815be71d)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/xattr.c (ffffffff815d31a4)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff815d9d2b)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff815da693)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff815db0fa)
Location: fs/ext4/ext4_jbd2.h:321
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
In fs/ext4/extents.c (ffffffff8159a308)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff815a233c)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815afe56)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815bc89a)
Location: fs/ext4/ext4_jbd2.h:321
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
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff815ce8b5)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff815d00c9)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
```
```
In fs/ext4/namei.c (ffffffff815d4c48)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/super.c (ffffffff815f542d)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/xattr.c (ffffffff8160ad11)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff8161190b)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff81612466)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff81612baa)
Location: fs/ext4/ext4_jbd2.h:321
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
In fs/ext4/extents.c (ffffffff815d3158)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/file.c (ffffffff815db065)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815e8c06)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815f5679)
Location: fs/ext4/ext4_jbd2.h:321
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
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81607135)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8160894f)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8160d2f1)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/super.c (ffffffff8162dd84)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_release_dquot
  - fs/ext4/super.c:ext4_acquire_dquot
  - fs/ext4/super.c:ext4_write_dquot
```
```
In fs/ext4/xattr.c (ffffffff81643ad1)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff8164a6be)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff8164b136)
Location: fs/ext4/ext4_jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8164b92a)
Location: fs/ext4/ext4_jbd2.h:321
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
In fs/ext4/extents.c (ffff80001046c840)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffff80001047cc68)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffff800010489628)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffff80001048cb90)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffff800010498b18)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffff80001049a1b8)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffff80001049df58)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffff8000104acb10)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (ffff8000104c63d8)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffff8000104c7ca8)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffff8000104c8828)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (c062dcb4)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (c063e714)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (c064bb78)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (c064e3a8)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (c065a718)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (c065ba74)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (c065fc2c)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (c06751e8)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (c068a41c)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (c068b938)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (c068c204)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (c00000000058c288)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (c0000000005a07d0)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (c0000000005b07d8)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (c0000000005b3688)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (c0000000005c2ec8)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (c0000000005c4780)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (c0000000005c98bc)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (c0000000005e4cb4)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (c0000000005fe994)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (c000000000600240)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (c000000000600f48)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffe0002f9d00)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffffffe000306aea)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffe000310ed8)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffe000312ae4)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffe00031ca26)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffe00031d9dc)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffe000320aca)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffe00032fe62)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (ffffffe0003408b6)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffe000341a02)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffe0003421b2)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff81392410)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffffffff813a1943)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813ad475)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813af718)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813b9c3f)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813bae3b)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813bea44)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff813d19bb)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (ffffffff813e5d15)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff813e6def)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff813e7981)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff81382ea0)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffffffff813923d3)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8139df05)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813a01a8)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813aa6cf)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813ab8cb)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813af4d4)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff813c243b)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (ffffffff813d6795)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff813d786f)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff813d8401)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff8138fd70)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffffffff8139f1a3)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813aacd5)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813acf78)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813b749f)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813b869b)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813bc024)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff813cee4b)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (ffffffff813e3095)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff813e416f)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff813e4d01)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents.c (ffffffff813a3bcb)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/inline.c (ffffffff813b3713)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813bf620)
Location: fs/ext4/ext4_jbd2.h:307
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
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813c1918)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff813cc1af)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813cd3bb)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813d0fd4)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff813e417b)
Location: fs/ext4/ext4_jbd2.h:307
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
In fs/ext4/xattr.c (ffffffff813f84a5)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff813f957f)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/verity.c (ffffffff813fa151)
Location: fs/ext4/ext4_jbd2.h:307
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
</details>
</li>
</ul>

## Differences
