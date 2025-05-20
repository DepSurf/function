# Function: <code>ext4_set_inode_state</code>

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
In fs/ext4/ialloc.c (ffffffff81295171)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81299a18)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/ext4/ioctl.c (ffffffff812a0a5c)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812a615d)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/extents.c (ffffffff812c3396)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff812cc787)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff812d743c)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/xattr.c (ffffffff812dcd61)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/inline.c (ffffffff812dfe12)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
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
In fs/ext4/ialloc.c (ffffffff812c28ac)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812cdc00)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/ioctl.c (ffffffff812cf78c)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812d517e)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/extents.c (ffffffff812f9d5b)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff812fc0ca)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81307184)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/xattr.c (ffffffff8130e82e)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/inline.c (ffffffff8130fac0)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
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
In fs/ext4/ialloc.c (ffffffff812d7ebf)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812e39dc)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/ioctl.c (ffffffff812e55b8)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812eae7e)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/extents.c (ffffffff8130fd2b)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff8131207a)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8131d15e)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/xattr.c (ffffffff81324599)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/inline.c (ffffffff81328b79)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
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
In fs/ext4/extents.c (ffffffff812ee31d)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/ialloc.c (ffffffff812f60ec)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff812fcb59)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81307c25)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/ioctl.c (ffffffff81308d55)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff81313b1f)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81315c16)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff8131aace)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff8133dbde)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
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
In fs/ext4/extents.c (ffffffff81312de0)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/ialloc.c (ffffffff8131a778)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813213b9)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8132c875)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/ioctl.c (ffffffff8132dbd6)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff813382df)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8133a476)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/namei.c (ffffffff8133f20e)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff813621be)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
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
In fs/ext4/extents.c (ffffffff8133ba79)
Location: fs/ext4/ext4.h:1569
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813484b8)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8134f3d8)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8135ae6a)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff81366869)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8136d148)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff81390978)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
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
In fs/ext4/extents.c (ffffffff81353129)
Location: fs/ext4/ext4.h:1582
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81360668)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff81367588)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8137312a)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff8137ecbc)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813855c8)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff813a9558)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
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
In fs/ext4/extents.c (ffffffff8137c4f6)
Location: fs/ext4/ext4.h:1599
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813897d2)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff81390949)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8139c5d3)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff813a810b)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813af5ad)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff813d3ad6)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
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
In fs/ext4/extents.c (ffffffff813949c6)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813a2102)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813a93a9)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813b50e3)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff813c0f5d)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813c8505)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff813ed1b6)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (ffffffff813eec9e)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
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
In fs/ext4/extents.c (ffffffff813e0aea)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff813ee1ec)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813f52f6)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81400540)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff8140d4fd)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff814143ae)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff8143a165)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (ffffffff8143be68)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
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
In fs/ext4/extents.c (ffffffff813f2377)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff81400830)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff81407a96)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81412da2)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff8142095d)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff814279b6)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff81452c75)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/fast_commit.c (ffffffff814561f4)
Location: fs/ext4/ext4.h:1856
Inline: True
```
```
In fs/ext4/verity.c (ffffffff814581c8)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
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
In fs/ext4/extents.c (ffffffff813f87f4)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff81406ce0)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8140df06)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81419202)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff81427118)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8142e62a)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff814584a5)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/fast_commit.c (ffffffff8145bc96)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
```
In fs/ext4/verity.c (ffffffff8145dd28)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
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
In fs/ext4/extents.c (ffffffff8144ac8a)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff81459564)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff81460dc6)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8146c448)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff8147adac)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81482563)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff814ac5a5)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/fast_commit.c (ffffffff814af396)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
```
In fs/ext4/orphan.c (ffffffff814b1c2e)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/ext4/verity.c (ffffffff814b31e8)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
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
In fs/ext4/extents.c (ffffffff814c7407)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff814d6f6e)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff814df7c7)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff814ec44c)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff814fd1de)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff815054e5)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff81534564)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/fast_commit.c (ffffffff81536d56)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
```
In fs/ext4/orphan.c (ffffffff8153a802)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/ext4/verity.c (ffffffff8153bbb7)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff8155fa37)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff8156fcf3)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8157890b)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815861b7)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff815979a1)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8159fff5)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff815d2a84)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/fast_commit.c (ffffffff815d51f6)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
```
In fs/ext4/orphan.c (ffffffff815d8d95)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/ext4/verity.c (ffffffff815da241)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff815977b5)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff815a7b75)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff815afeab)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
```
```
In fs/ext4/inode.c (ffffffff815b84e8)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/migrate.c (ffffffff815ce3d8)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff815d69f1)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff8160a593)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/fast_commit.c (ffffffff8160cdb6)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
```
In fs/ext4/orphan.c (ffffffff81610932)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/ext4/verity.c (ffffffff81611f84)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffffffff815d0465)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_precache
```
```
In fs/ext4/ialloc.c (ffffffff815e098c)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff815e8c5b)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
```
```
In fs/ext4/inode.c (ffffffff815f1288)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
```
```
In fs/ext4/migrate.c (ffffffff81606c58)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff8160f02b)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff8164334c)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/fast_commit.c (ffffffff81645b76)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
```
In fs/ext4/orphan.c (ffffffff816496f2)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_cleanup
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/ext4/verity.c (ffffffff8164ad24)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/extents.c (ffff800010467694)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/ialloc.c (ffff8000104757d4)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffff80001047cca8)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffff800010489898)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffff800010498780)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffff80001049fea8)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffff8000104c5e4c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (ffff8000104c86c8)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
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
In fs/ext4/extents.c (c06282fc)
Location: fs/ext4/ext4.h:1637
Inline: True
```
```
In fs/ext4/ialloc.c (c0636fc4)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (c063e758)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (c064bddc)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (c0659ff0)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (c0661ba0)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (c0689e64)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (c068beb0)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
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
In fs/ext4/extents.c (c000000000585b04)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/ialloc.c (c0000000005973b0)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (c0000000005a082c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (c0000000005b0908)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (c0000000005c26e4)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (c0000000005cbee4)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (c0000000005fe298)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (c000000000600b3c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
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
In fs/ext4/extents.c (ffffffe0002f555e)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffe00030122a)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffe000306b18)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffe000310fa0)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffe00031c506)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffe00032239c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffe00034043c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (ffffffe000341f28)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
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
In fs/ext4/extents.c (ffffffff8138cfa6)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8139a6e2)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813a1989)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813ad6c3)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff813b953d)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813c0ae5)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff813e5796)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (ffffffff813e727e)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
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
In fs/ext4/extents.c (ffffffff8137da36)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8138b172)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff81392419)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8139e153)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff813a9fcd)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813b1575)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff813d6216)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (ffffffff813d7cfe)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
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
In fs/ext4/extents.c (ffffffff8138a906)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81397f42)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8139f1e9)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813aaf23)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff813b6d9d)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813be05e)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff813e2b16)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (ffffffff813e45fe)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
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
In fs/ext4/extents.c (ffffffff8139e646)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813abd1c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813b3759)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813bf86e)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/migrate.c (ffffffff813cbaad)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff813d3075)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
```
In fs/ext4/xattr.c (ffffffff813f7f26)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (ffffffff813f9a0e)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
</details>
</li>
</ul>

## Differences
