# Function: <code>ext4_handle_valid</code>

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
In fs/ext4/ialloc.c (ffffffff8129509c)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8129882a)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff812a092f)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812a46c0)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_link
```
```
In fs/ext4/resize.c (ffffffff812beee4)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff812c31d7)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812cb762)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
```
```
In fs/ext4/migrate.c (ffffffff812cc0ae)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mballoc.c (ffffffff812cde25)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/move_extent.c (ffffffff812d7155)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/indirect.c (ffffffff812d8817)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/indirect.c:try_to_extend_transaction
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff812dd117)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/inline.c (ffffffff812e2901)
Location: fs/ext4/ext4_jbd2.h:270
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
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
In fs/ext4/ialloc.c (ffffffff812c27d4)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812cd787)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff812cee7a)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/namei.c (ffffffff812d3681)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff812ee80d)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff812fa048)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812fb8d0)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/migrate.c (ffffffff812fc186)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/mballoc.c (ffffffff8130466c)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/move_extent.c (ffffffff81306e8d)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/indirect.c (ffffffff813096ce)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130e40c)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/inline.c (ffffffff813128b4)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
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
In fs/ext4/ialloc.c (ffffffff812d7ded)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812e354f)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff812e4d7e)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/namei.c (ffffffff812e93d1)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff813047dd)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff81310019)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81311880)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/migrate.c (ffffffff81312136)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/mballoc.c (ffffffff8131a62c)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/move_extent.c (ffffffff8131ce31)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/indirect.c (ffffffff8131f6de)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff81324180)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/inline.c (ffffffff81328840)
Location: fs/ext4/ext4_jbd2.h:278
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
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
In fs/ext4/ext4_jbd2.c (ffffffff812e6740)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff812ee59b)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ialloc.c (ffffffff812f607f)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff812f7702)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff812fc8da)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff8130773c)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff813085c1)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff81311a18)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff81313bd8)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffffffff813159e6)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff81318bc1)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff8131f36f)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff8133dbe6)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (ffffffff8130b150)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff81313064)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ialloc.c (ffffffff8131a6e7)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8131bd42)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8132113a)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff8132c38a)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff8132d011)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff81336290)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff81338398)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffffffff8133a20c)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff8133d355)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff81343a0f)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813621c6)
Location: fs/ext4/ext4_jbd2.h:274
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (ffffffff813390a0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff81340f5d)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/ialloc.c (ffffffff813483b0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff81349c3f)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8134f117)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff8135a9b3)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff8135b734)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff8136491a)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff81366933)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffffffff81368722)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff8136b8fd)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff8137183c)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff81390980)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (ffffffff81350350)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff8135856d)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/ialloc.c (ffffffff81360560)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff81361dff)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813672c7)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff81372c73)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff813739b4)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff8137cba0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff8137ed88)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffffffff81380ba6)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff81383dbd)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff81389d03)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813a9560)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (ffffffff81379001)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff81381a5d)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/ialloc.c (ffffffff813896e0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8138b296)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8139063d)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff8139c0c2)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff8139cfe4)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813a6838)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff813a81d7)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffffffff813a9f00)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813ad57f)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff813b476b)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813d3adf)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (ffffffff813913c1)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff8139a00d)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/ialloc.c (ffffffff813a2010)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff813a3ce6)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813a909d)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff813b4bd2)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff813b5a54)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813bf6b9)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff813c1029)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffffffff813c2e30)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813c64b3)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff813cd66b)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813ed1bf)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (ffffffff813dcc71)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff813e371f)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/ialloc.c (ffffffff813ee113)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff813eff34)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813f4ff8)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff81400079)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81401140)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff8140b74d)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/migrate.c (ffffffff8140d616)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8140f3f5)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81412956)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
```
```
In fs/ext4/resize.c (ffffffff81419bf8)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff8143ac7c)
Location: fs/ext4/ext4_jbd2.h:275
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/ext4_jbd2.c (ffffffff813ee504)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff813f4f40)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/ialloc.c (ffffffff8140075b)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff81402692)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81407781)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff81412d76)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81413a00)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff8141ebd5)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/migrate.c (ffffffff81420a76)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff814228b4)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81425dfa)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
```
```
In fs/ext4/resize.c (ffffffff8142d898)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff814537ec)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/ext4_jbd2.c (ffffffff813f4ad0)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff813fb284)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/ialloc.c (ffffffff81406c0b)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff81408a8f)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8140dbf1)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff814191da)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81419c63)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff8142565b)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/migrate.c (ffffffff81427231)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff814290c3)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8142c9ed)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
```
```
In fs/ext4/resize.c (ffffffff81434558)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff8145910c)
Location: fs/ext4/ext4_jbd2.h:267
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/ext4_jbd2.c (ffffffff81446d20)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff8144d66a)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/ialloc.c (ffffffff8145948f)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8145b509)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81460a96)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff8146c420)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8146ce53)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff81479279)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/migrate.c (ffffffff8147aec8)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8147cee3)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
```
```
In fs/ext4/namei.c (ffffffff814808ed)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
```
```
In fs/ext4/resize.c (ffffffff81487fd4)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff814ad21c)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/ext4_jbd2.c (ffffffff814c3028)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff814ca15d)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/ialloc.c (ffffffff814d6e78)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff814d92c6)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff814df445)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff814ec428)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff814ec7fe)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff814f5915)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
```
```
In fs/ext4/migrate.c (ffffffff814fd2f6)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff814ff6e7)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8150382c)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
```
```
In fs/ext4/resize.c (ffffffff8150d5a5)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff815352b7)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/ext4_jbd2.c (ffffffff8155b3ba)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff815627d8)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/ialloc.c (ffffffff8156fbfd)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff81572106)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff81578550)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff81586193)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8158657f)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff8158fc05)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
```
```
In fs/ext4/migrate.c (ffffffff81597ac2)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81599e7f)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8159e38b)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
```
```
In fs/ext4/resize.c (ffffffff815a83b1)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff815d36f7)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/ext4_jbd2.c (ffffffff815931df)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff8159a506)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/ialloc.c (ffffffff815a7a7f)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff815a9e96)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff815afab9)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff815bc3bc)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815bccbf)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff815c6e36)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff815ce502)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff815d0779)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
```
```
In fs/ext4/namei.c (ffffffff815d4c9b)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
```
```
In fs/ext4/resize.c (ffffffff815dec31)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff8160b2a7)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/ext4_jbd2.c (ffffffff815cbecf)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff815d3349)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
```
```
In fs/ext4/ialloc.c (ffffffff815e0896)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff815e2c36)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff815e886e)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff815f519c)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f5a9d)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff81601b2c)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff81606d82)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8160900b)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8160d344)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
```
```
In fs/ext4/resize.c (ffffffff816176ed)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/xattr.c (ffffffff81644067)
Location: fs/ext4/ext4_jbd2.h:273
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/ext4_jbd2.c (ffff800010463fb0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffff80001046ca04)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/ialloc.c (ffff800010475758)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffff800010477350)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffff80001047ca0c)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffff800010489398)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffff80001048ac98)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffff800010496390)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffff8000104987cc)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffff80001049a71c)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffff80001049dfc8)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffff8000104a6c0c)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffff8000104c5e6c)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (c06245b0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (c062dee0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/ialloc.c (c0636f28)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (c0638f04)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c063e4f0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (c064b874)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (c064c24c)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (c0658104)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (c065a114)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (c065c0c4)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (c065fcb0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (c06689e0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (c0689e6c)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (c00000000058130c)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (c00000000058c4e0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
```
In fs/ext4/ialloc.c (c0000000005972c8)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (c000000000599550)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c0000000005a054c)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (c0000000005b02b0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (c0000000005b1690)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (c0000000005c0260)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (c0000000005c27b4)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (c0000000005c4eac)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (c0000000005c9930)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (c0000000005d32b0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (c0000000005fe2a8)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (ffffffe0002f2682)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffe0002f9e9e)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/ialloc.c (ffffffe00030116c)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffe000302686)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffe00030696c)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffe000310b80)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffe000311826)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffe00031ae56)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffe00031c63a)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffffffe00031deb6)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffe000320b16)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffe000326c10)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffe000340450)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (ffffffff813899a1)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff813925ed)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/ialloc.c (ffffffff8139a5f0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8139c2c6)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813a167d)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff813ad1b2)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff813ae034)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813b7c99)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff813b9609)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffffffff813bb410)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813bea93)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff813c5c4b)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813e579f)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (ffffffff8137a431)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff8138307d)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/ialloc.c (ffffffff8138b080)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff8138cd56)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8139210d)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff8139dc42)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff8139eac4)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813a8729)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff813aa099)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffffffff813abea0)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813af523)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff813b66cb)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813d621f)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (ffffffff81387301)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff8138ff4d)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/ialloc.c (ffffffff81397e50)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff81399b26)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8139eedd)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff813aaa12)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff813ab894)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813b54f9)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff813b6e69)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffffffff813b8c70)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813bc073)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff813c30db)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813e2b1f)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
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
In fs/ext4/ext4_jbd2.c (ffffffff8139afe1)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
```
```
In fs/ext4/extents.c (ffffffff813a3db2)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/ialloc.c (ffffffff813abc29)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/indirect.c (ffffffff813adc16)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813b344d)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff813bf362)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
```
```
In fs/ext4/ioctl.c (ffffffff813c0234)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813ca16f)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/migrate.c (ffffffff813cbb79)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/move_extent.c (ffffffff813cd990)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/namei.c (ffffffff813d1023)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/resize.c (ffffffff813d828b)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/xattr.c (ffffffff813f7f2f)
Location: fs/ext4/ext4_jbd2.h:271
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
</details>
</li>
</ul>

## Differences
