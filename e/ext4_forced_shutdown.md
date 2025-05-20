# Function: <code>ext4_forced_shutdown</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff812e62c4)
Location: fs/ext4/ext4.h:1860
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
```
In fs/ext4/file.c (ffffffff812f0ed6)
Location: fs/ext4/ext4.h:1860
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff812f339c)
Location: fs/ext4/ext4.h:1860
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812f5130)
Location: fs/ext4/ext4.h:1860
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff812f9190)
Location: fs/ext4/ext4.h:1860
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81302e61)
Location: fs/ext4/ext4.h:1860
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff81308bcb)
Location: fs/ext4/ext4.h:1860
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff8131c890)
Location: fs/ext4/ext4.h:1860
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffff8131dd49)
Location: fs/ext4/ext4.h:1860
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff8132b76a)
Location: fs/ext4/ext4.h:1860
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff8133d00e)
Location: fs/ext4/ext4.h:1860
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff8130acd4)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff81315b05)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff8131792c)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81319887)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8131d7d0)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81327851)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff8132d842)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff813417ab)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffff81342359)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff8134fbca)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff813615ee)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff81338829)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff81343f72)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff813457cb)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81347624)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8134b760)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813554e0)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff8135c5ec)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff8136ee50)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffff813701b9)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff81383fb2)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff8138fdbe)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff8134fad9)
Location: fs/ext4/ext4.h:1836
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff8135c0b2)
Location: fs/ext4/ext4.h:1836
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff8135d91c)
Location: fs/ext4/ext4.h:1836
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8135f7d4)
Location: fs/ext4/ext4.h:1836
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813638a0)
Location: fs/ext4/ext4.h:1836
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8136d810)
Location: fs/ext4/ext4.h:1836
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff81374614)
Location: fs/ext4/ext4.h:1836
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff813872e0)
Location: fs/ext4/ext4.h:1836
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffff81388649)
Location: fs/ext4/ext4.h:1836
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff8139ca92)
Location: fs/ext4/ext4.h:1836
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff813a8a07)
Location: fs/ext4/ext4.h:1836
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff8137876b)
Location: fs/ext4/ext4.h:1858
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff81385271)
Location: fs/ext4/ext4.h:1858
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff81386ad3)
Location: fs/ext4/ext4.h:1858
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81388984)
Location: fs/ext4/ext4.h:1858
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8138cb30)
Location: fs/ext4/ext4.h:1858
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81396e20)
Location: fs/ext4/ext4.h:1858
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff8139dc65)
Location: fs/ext4/ext4.h:1858
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff813b12e0)
Location: fs/ext4/ext4.h:1858
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffff813b272a)
Location: fs/ext4/ext4.h:1858
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813ca012)
Location: fs/ext4/ext4.h:1858
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff813d2c14)
Location: fs/ext4/ext4.h:1858
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff81390b2b)
Location: fs/ext4/ext4.h:1916
Inline: True
```
```
In fs/ext4/file.c (ffffffff8139dd14)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff8139f523)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813a133b)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813a5580)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813af850)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff813b704b)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff813ca330)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffff813cb77a)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813e3312)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff813ec2f4)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff813dc1eb)
Location: fs/ext4/ext4.h:2014
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff813e97da)
Location: fs/ext4/ext4.h:2014
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff813eb434)
Location: fs/ext4/ext4.h:2014
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813ed5e3)
Location: fs/ext4/ext4.h:2014
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813f13c0)
Location: fs/ext4/ext4.h:2014
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813fb890)
Location: fs/ext4/ext4.h:2014
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff814013b3)
Location: fs/ext4/ext4.h:2014
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/namei.c (ffffffff81415bd0)
Location: fs/ext4/ext4.h:2014
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffff814178d1)
Location: fs/ext4/ext4.h:2014
Inline: True
```
```
In fs/ext4/super.c (ffffffff81430242)
Location: fs/ext4/ext4.h:2014
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff814395e0)
Location: fs/ext4/ext4.h:2014
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff813edc7b)
Location: fs/ext4/ext4.h:2139
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff813fb8da)
Location: fs/ext4/ext4.h:2139
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff813fd661)
Location: fs/ext4/ext4.h:2139
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813ffd81)
Location: fs/ext4/ext4.h:2139
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff81403aa0)
Location: fs/ext4/ext4.h:2139
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8140e010)
Location: fs/ext4/ext4.h:2139
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff81413c6d)
Location: fs/ext4/ext4.h:2139
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/namei.c (ffffffff81429440)
Location: fs/ext4/ext4.h:2139
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/page-io.c (ffffffff8142b3d1)
Location: fs/ext4/ext4.h:2139
Inline: True
```
```
In fs/ext4/super.c (ffffffff81448f82)
Location: fs/ext4/ext4.h:2139
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff81452100)
Location: fs/ext4/ext4.h:2139
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff813f425b)
Location: fs/ext4/ext4.h:2148
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff81401beb)
Location: fs/ext4/ext4.h:2148
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff81403a71)
Location: fs/ext4/ext4.h:2148
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81406128)
Location: fs/ext4/ext4.h:2148
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8140a154)
Location: fs/ext4/ext4.h:2148
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff814141d0)
Location: fs/ext4/ext4.h:2148
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff81419edd)
Location: fs/ext4/ext4.h:2148
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/namei.c (ffffffff81430110)
Location: fs/ext4/ext4.h:2148
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/page-io.c (ffffffff81431fe4)
Location: fs/ext4/ext4.h:2148
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff8144e902)
Location: fs/ext4/ext4.h:2148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff81457840)
Location: fs/ext4/ext4.h:2148
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff8144639b)
Location: fs/ext4/ext4.h:2219
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff8145435b)
Location: fs/ext4/ext4.h:2219
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff81456241)
Location: fs/ext4/ext4.h:2219
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81458988)
Location: fs/ext4/ext4.h:2219
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8145cce4)
Location: fs/ext4/ext4.h:2219
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81467530)
Location: fs/ext4/ext4.h:2219
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff8146d0cd)
Location: fs/ext4/ext4.h:2219
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/namei.c (ffffffff81484760)
Location: fs/ext4/ext4.h:2219
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/page-io.c (ffffffff81485833)
Location: fs/ext4/ext4.h:2219
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff814a2362)
Location: fs/ext4/ext4.h:2219
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff814ab920)
Location: fs/ext4/ext4.h:2219
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff814c24e9)
Location: fs/ext4/ext4.h:2221
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff814d1a8b)
Location: fs/ext4/ext4.h:2221
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff814d3c41)
Location: fs/ext4/ext4.h:2221
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff814d655f)
Location: fs/ext4/ext4.h:2221
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff814daff4)
Location: fs/ext4/ext4.h:2221
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff814e715b)
Location: fs/ext4/ext4.h:2221
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff814ecb7d)
Location: fs/ext4/ext4.h:2221
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/namei.c (ffffffff815078f0)
Location: fs/ext4/ext4.h:2221
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/page-io.c (ffffffff81508cc2)
Location: fs/ext4/ext4.h:2221
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff81529662)
Location: fs/ext4/ext4.h:2221
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff815337a4)
Location: fs/ext4/ext4.h:2221
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff8155a749)
Location: fs/ext4/ext4.h:2231
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff81569b9a)
Location: fs/ext4/ext4.h:2231
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff8156c891)
Location: fs/ext4/ext4.h:2231
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8156f336)
Location: fs/ext4/ext4.h:2231
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff815744a4)
Location: fs/ext4/ext4.h:2231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81580afb)
Location: fs/ext4/ext4.h:2231
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff8158692d)
Location: fs/ext4/ext4.h:2231
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/namei.c (ffffffff815a23f0)
Location: fs/ext4/ext4.h:2231
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/page-io.c (ffffffff815a3822)
Location: fs/ext4/ext4.h:2231
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff815c7e02)
Location: fs/ext4/ext4.h:2231
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff815d1d74)
Location: fs/ext4/ext4.h:2231
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff81592569)
Location: fs/ext4/ext4.h:2225
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff815a198a)
Location: fs/ext4/ext4.h:2225
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff815a472e)
Location: fs/ext4/ext4.h:2225
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff815a7166)
Location: fs/ext4/ext4.h:2225
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff815ac2f4)
Location: fs/ext4/ext4.h:2225
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff815b80ab)
Location: fs/ext4/ext4.h:2225
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff815be9ae)
Location: fs/ext4/ext4.h:2225
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_force_shutdown
```
```
In fs/ext4/namei.c (ffffffff815d8d90)
Location: fs/ext4/ext4.h:2225
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/page-io.c (ffffffff815da2b2)
Location: fs/ext4/ext4.h:2225
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff815ffc12)
Location: fs/ext4/ext4.h:2225
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff81609814)
Location: fs/ext4/ext4.h:2225
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff815cb282)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (ffffffff815db18b)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_splice_read
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff815dd567)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff815dffb8)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff815e5065)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff815f0e35)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff815f775e)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_force_shutdown
```
```
In fs/ext4/mmp.c (ffffffff816078b2)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/namei.c (ffffffff81611405)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
```
In fs/ext4/page-io.c (ffffffff81612a6b)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff8163b10f)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff81642545)
Location: fs/ext4/ext4.h:2243
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffff800010463510)
Location: fs/ext4/ext4.h:1916
Inline: True
```
```
In fs/ext4/file.c (ffff800010471290)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffff800010472944)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffff800010474bc0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffff800010478bd8)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffff8000104842cc)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffff80001048c860)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffff8000104a1e88)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffff8000104a37e4)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffff8000104bc8ac)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffff8000104c5214)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (c0623bc0)
Location: fs/ext4/ext4.h:1916
Inline: True
```
```
In fs/ext4/file.c (c0632028)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (c0633d6c)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (c0636180)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (c063a6d0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (c0645900)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (c064e0f0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (c06640d8)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (c06656c0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (c067ff34)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (c06892c4)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (c000000000580580)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/file.c (c000000000591a88)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (c000000000593798)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (c00000000059634c)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (c00000000059b3e8)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (c0000000005a9460)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (c0000000005b2464)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (c0000000005ceb38)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (c0000000005d075c)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (c0000000005f26a8)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (c0000000005fceac)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffe0002f1eca)
Location: fs/ext4/ext4.h:1916
Inline: True
```
```
In fs/ext4/file.c (ffffffe0002fd516)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffe0002fe7e0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffe0003005e4)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffe000303ab2)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffe00030c7b0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffe000312992)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffe000323d1e)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffe0003250b8)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffe0003385e2)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffe00033faaa)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff8138910b)
Location: fs/ext4/ext4.h:1916
Inline: True
```
```
In fs/ext4/file.c (ffffffff813962f4)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff81397b03)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8139991b)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8139db60)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813a7e30)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff813af62b)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff813c2910)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffff813c3d5a)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813db8f2)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff813e48d4)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff81379b9b)
Location: fs/ext4/ext4.h:1916
Inline: True
```
```
In fs/ext4/file.c (ffffffff81386d84)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff81388593)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8138a3ab)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8138e5f0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813988c0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff813a00bb)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff813b33a0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffff813b47da)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813cc372)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff813d5354)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff81386a6b)
Location: fs/ext4/ext4.h:1916
Inline: True
```
```
In fs/ext4/file.c (ffffffff81393c54)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff81395463)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8139717b)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff8139b3c0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813a5690)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff813ace8b)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff813bfdc0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffff813c11ea)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813d8d92)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff813e1c54)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/ext4_jbd2.c (ffffffff8139a73c)
Location: fs/ext4/ext4.h:1916
Inline: True
```
```
In fs/ext4/file.c (ffffffff813a7ce4)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/fsync.c (ffffffff813a9583)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813ab49c)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffff813af880)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813b9dd0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/ioctl.c (ffffffff813c182b)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff813d4ea0)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename2
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/page-io.c (ffffffff813d634a)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813ee082)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/xattr.c (ffffffff813f7064)
Location: fs/ext4/ext4.h:1916
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
```
</details>
</li>
</ul>

## Differences
