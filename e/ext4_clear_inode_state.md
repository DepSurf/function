# Function: <code>ext4_clear_inode_state</code>

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
In fs/ext4/file.c (ffffffff81291963)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff81292d18)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81295edb)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff812a0bc1)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/extents.c (ffffffff812c33eb)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff812ccab5)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff812d7808)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/xattr.c (ffffffff812dcd50)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/inline.c (ffffffff812df87b)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_convert_inline_data
```
```
In fs/ext4/crypto_policy.c (ffffffff812e4d8a)
Location: fs/ext4/ext4.h:1519
Inline: True
Inline callers:
  - fs/ext4/crypto_policy.c:ext4_inherit_context
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
In fs/ext4/file.c (ffffffff812beec8)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff812c031a)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff812cd74b)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff812cf8eb)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812e7397)
Location: fs/ext4/ext4.h:1596
Inline: True
```
```
In fs/ext4/extents.c (ffffffff812f9dcb)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff812fc42b)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8130755c)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/xattr.c (ffffffff8130ec71)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/inline.c (ffffffff81312b5e)
Location: fs/ext4/ext4.h:1596
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
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
In fs/ext4/file.c (ffffffff812d44e8)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff812d594d)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff812e3513)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff812e56f8)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812fd105)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/extents.c (ffffffff8130fd9b)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff813123db)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8131d515)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/xattr.c (ffffffff81324a02)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/inline.c (ffffffff81328ae0)
Location: fs/ext4/ext4.h:1601
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
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
In fs/ext4/extents.c (ffffffff812ee384)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/file.c (ffffffff812f0e66)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff812f365a)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff812fcac0)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81307700)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81308f54)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff81313dc3)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81315e87)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff81331d5b)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff8133dcf7)
Location: fs/ext4/ext4.h:1606
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/extents.c (ffffffff81312e4d)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/file.c (ffffffff81315a96)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff81317bf4)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff81321320)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8132c34e)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8132dda5)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffff81338583)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8133a6f0)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/super.c (ffffffff81356150)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813622d7)
Location: fs/ext4/ext4.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
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
In fs/ext4/file.c (ffffffff813438a6)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff81345a62)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8134f330)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813558a4)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff81366b44)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813844e0)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff81390a92)
Location: fs/ext4/ext4.h:1569
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
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
In fs/ext4/file.c (ffffffff8135b9e6)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff8135dbd9)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813674e0)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8136dbd4)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff8137efb4)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8139cfc0)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813a9672)
Location: fs/ext4/ext4.h:1582
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
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
In fs/ext4/file.c (ffffffff813851f6)
Location: fs/ext4/ext4.h:1599
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81386d70)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813908b0)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8139724f)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff813a83b6)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813c71e1)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813d3b91)
Location: fs/ext4/ext4.h:1599
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
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
In fs/ext4/extents_status.c (ffffffff8139cfca)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff8139dc96)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff8139f7c0)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813a9310)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813afc7f)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff813c1277)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813e05a1)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813ed271)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff813ef398)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (ffffffff813e870a)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff813e9768)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff813eb385)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_parent
```
```
In fs/ext4/inline.c (ffffffff813f5244)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813fbac5)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff8140d17b)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/super.c (ffffffff8142d3f3)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff8143a29f)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff8143c147)
Location: fs/ext4/ext4.h:1739
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (ffffffff813fa9ba)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff813fb418)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff813fd5b5)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_parent
```
```
In fs/ext4/inline.c (ffffffff814079e4)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8140e214)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff814205db)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/super.c (ffffffff814461c3)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff81452dce)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/fast_commit.c (ffffffff81455c2c)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/verity.c (ffffffff814584b2)
Location: fs/ext4/ext4.h:1856
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (ffffffff81400d7a)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff814018e8)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff81403c13)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8140de54)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81414584)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff81426cab)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/super.c (ffffffff8144b98f)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff814585fe)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/fast_commit.c (ffffffff8145b849)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/verity.c (ffffffff8145de54)
Location: fs/ext4/ext4.h:1865
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (ffffffff8145338a)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff81453e78)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff81456495)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff81460d14)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81467904)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff8147a93b)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/super.c (ffffffff8149f98f)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff814ac705)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/fast_commit.c (ffffffff814af114)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff814b17d9)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
```
```
In fs/ext4/verity.c (ffffffff814b3371)
Location: fs/ext4/ext4.h:1927
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (ffffffff814d094f)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff814d0e5e)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff814d3f03)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff814df6f8)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff814e759d)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff814fcd24)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/xattr.c (ffffffff81534666)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/fast_commit.c (ffffffff815361bf)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff8153a33b)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
```
```
In fs/ext4/verity.c (ffffffff8153bf58)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8153ca0d)
Location: fs/ext4/ext4.h:1929
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
In fs/ext4/extents_status.c (ffffffff815692ff)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff8156ab43)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff8156cb82)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff81578838)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81580f5d)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff815974b4)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/xattr.c (ffffffff815d2b86)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/fast_commit.c (ffffffff815d46bf)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff815d88ab)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
```
```
In fs/ext4/verity.c (ffffffff815da608)
Location: fs/ext4/ext4.h:1939
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff815db17e)
Location: fs/ext4/ext4.h:1939
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
In fs/ext4/extents_status.c (ffffffff815a0fb8)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff815a29b5)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff815a49d2)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff815afdd8)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815b850d)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff815cdeed)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/xattr.c (ffffffff8160a699)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/fast_commit.c (ffffffff8160c2af)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff8161039b)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
```
```
In fs/ext4/verity.c (ffffffff816123db)
Location: fs/ext4/ext4.h:1933
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff81612c2e)
Location: fs/ext4/ext4.h:1933
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
In fs/ext4/extents_status.c (ffffffff815d9d18)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff815db6b2)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff815dd811)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff815e8b88)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815f12ad)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff8160676d)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/xattr.c (ffffffff8164344e)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/fast_commit.c (ffffffff8164506f)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff8164915b)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
```
```
In fs/ext4/verity.c (ffffffff8164b0ab)
Location: fs/ext4/ext4.h:1951
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8164b9ae)
Location: fs/ext4/ext4.h:1951
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
In fs/ext4/extents_status.c (ffff800010470050)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffff8000104711e4)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffff800010472aac)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffff80001047cbd4)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffff800010484778)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffff800010498324)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/super.c (ffff8000104b97e4)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffff8000104c5f00)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffff8000104c8814)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (c0631594)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (c0631b94)
Location: fs/ext4/ext4.h:1637
Inline: True
```
```
In fs/ext4/fsync.c (c0633f48)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (c063e6bc)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (c0645cdc)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (c065a31c)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c067cf78)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (c0689f18)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (c068c1f8)
Location: fs/ext4/ext4.h:1637
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (c000000000590690)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (c000000000590e80)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (c000000000593990)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (c0000000005a0734)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (c0000000005a9a00)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (c0000000005c2a1c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c0000000005eed48)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (c0000000005fe354)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (c000000000600f2c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (ffffffe0002fc91c)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffe0002fd1fc)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffe0002fe940)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffe000306aa4)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffe00030cadc)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffe00031c672)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffe000335f30)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffe0003405b8)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffe0003421a4)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (ffffffff813955aa)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff81396276)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81397da0)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813a18f0)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813a825f)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff813b9857)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813d8b81)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813e5851)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff813e7978)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (ffffffff8138603a)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff81386d06)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81388830)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff81392380)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81398cef)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff813aa2e7)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813c9601)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813d62d1)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff813d83f8)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (ffffffff81392f0a)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff81393bd6)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81395700)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8139f150)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813a5abf)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff813b70b7)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813d6011)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813e2bd1)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff813e4cf8)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In fs/ext4/extents_status.c (ffffffff813a6f7f)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff813a7c66)
Location: fs/ext4/ext4.h:1644
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff813a984d)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813b36c0)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813ba213)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/migrate.c (ffffffff813cbdc7)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813eb2b1)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813f7fe1)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff813fa148)
Location: fs/ext4/ext4.h:1644
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
</details>
</li>
</ul>

## Differences
