# Function: <code>get_fuse_conn</code>

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
In fs/fuse/dev.c (0)
Location: fs/fuse/fuse_i.h:673
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:673
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:673
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:673
Inline: True
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
In fs/fuse/dev.c (0)
Location: fs/fuse/fuse_i.h:683
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:683
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:683
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:683
Inline: True
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
In fs/fuse/dev.c (0)
Location: fs/fuse/fuse_i.h:684
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:684
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:684
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:684
Inline: True
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:684
Inline: True
```
```
In fs/fuse/acl.c (0)
Location: fs/fuse/fuse_i.h:684
Inline: True
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
In fs/fuse/dev.c (0)
Location: fs/fuse/fuse_i.h:680
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: fs/fuse/fuse_i.h:680
Inline: True
```
```
In fs/fuse/file.c (0)
Location: fs/fuse/fuse_i.h:680
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: fs/fuse/fuse_i.h:680
Inline: True
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:680
Inline: True
```
```
In fs/fuse/acl.c (0)
Location: fs/fuse/fuse_i.h:680
Inline: True
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
In fs/fuse/dev.c (ffffffff81394ea3)
Location: fs/fuse/fuse_i.h:679
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_force_forget
```
```
In fs/fuse/dir.c (ffffffff81397a59)
Location: fs/fuse/fuse_i.h:679
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8139e1e2)
Location: fs/fuse/fuse_i.h:679
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffff8139e706)
Location: fs/fuse/fuse_i.h:679
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_unlock_inode
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/xattr.c (ffffffff813a0fc2)
Location: fs/fuse/fuse_i.h:679
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff813a11e2)
Location: fs/fuse/fuse_i.h:679
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
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
In fs/fuse/dev.c (ffffffff813c3fb7)
Location: fs/fuse/fuse_i.h:685
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_force_forget
```
```
In fs/fuse/dir.c (ffffffff813c6cc0)
Location: fs/fuse/fuse_i.h:685
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff813cd592)
Location: fs/fuse/fuse_i.h:685
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffff813cdb36)
Location: fs/fuse/fuse_i.h:685
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff813d03a2)
Location: fs/fuse/fuse_i.h:685
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff813d05b5)
Location: fs/fuse/fuse_i.h:685
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
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
In fs/fuse/dev.c (ffffffff813dd787)
Location: fs/fuse/fuse_i.h:753
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_force_forget
```
```
In fs/fuse/dir.c (ffffffff813dfe95)
Location: fs/fuse/fuse_i.h:753
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff813e6912)
Location: fs/fuse/fuse_i.h:753
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffff813e6f26)
Location: fs/fuse/fuse_i.h:753
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff813e9912)
Location: fs/fuse/fuse_i.h:753
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff813e9b25)
Location: fs/fuse/fuse_i.h:753
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff813e9f96)
Location: fs/fuse/fuse_i.h:753
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
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
In fs/fuse/dev.c (ffffffff814092b7)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_force_forget
```
```
In fs/fuse/dir.c (ffffffff8140ba94)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814127b2)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff81412f66)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/xattr.c (ffffffff81415a72)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff81415c85)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8141683a)
Location: fs/fuse/fuse_i.h:769
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/dir.c (ffffffff81425544)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8142c5c2)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8142d0b6)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/xattr.c (ffffffff8142f8b2)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff8142fad5)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8143075a)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_force_forget
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
In fs/fuse/dir.c (ffffffff814737a4)
Location: fs/fuse/fuse_i.h:765
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_fillattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81476aab)
Location: fs/fuse/fuse_i.h:765
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_compat_ioctl
  - fs/fuse/file.c:fuse_file_ioctl
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_file_lock
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8147c36b)
Location: fs/fuse/fuse_i.h:765
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff8147f571)
Location: fs/fuse/fuse_i.h:765
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff8147f935)
Location: fs/fuse/fuse_i.h:765
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff81480357)
Location: fs/fuse/fuse_i.h:765
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/dir.c (ffffffff8148f63c)
Location: fs/fuse/fuse_i.h:839
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_fillattr
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/file.c (ffffffff814918bd)
Location: fs/fuse/fuse_i.h:839
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_compat_ioctl
  - fs/fuse/file.c:fuse_file_ioctl
  - fs/fuse/file.c:fuse_file_lock
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8149737b)
Location: fs/fuse/fuse_i.h:839
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/acl.c (ffffffff8149b005)
Location: fs/fuse/fuse_i.h:839
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8149ba37)
Location: fs/fuse/fuse_i.h:839
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/dax.c (ffffffff8149e1c5)
Location: fs/fuse/fuse_i.h:839
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
In fs/fuse/dir.c (ffffffff8149505c)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/file.c (ffffffff81499c65)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_lock
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8149c4e1)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/acl.c (ffffffff814a0255)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff814a0b57)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff814a1fdd)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff814a4195)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
In fs/fuse/dir.c (ffffffff814ecaec)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/file.c (ffffffff814f1685)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_lock
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff814f66f7)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/acl.c (ffffffff814f8275)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff814f8a24)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff814fa07d)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff814fc235)
Location: fs/fuse/fuse_i.h:853
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
In fs/fuse/dir.c (ffffffff8157b85a)
Location: fs/fuse/fuse_i.h:874
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/file.c (ffffffff81581055)
Location: fs/fuse/fuse_i.h:874
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_lock
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_writepage
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff81586527)
Location: fs/fuse/fuse_i.h:874
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/acl.c (ffffffff81588315)
Location: fs/fuse/fuse_i.h:874
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff81589004)
Location: fs/fuse/fuse_i.h:874
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff8158a2ea)
Location: fs/fuse/fuse_i.h:874
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff8158c865)
Location: fs/fuse/fuse_i.h:874
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
In fs/fuse/dir.c (ffffffff8162121a)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_tmpfile
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/file.c (ffffffff81626e65)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_lock
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_writepage
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8162c7a7)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/acl.c (ffffffff8162e7ad)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_inode_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8162f517)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff81630a4a)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff81633155)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
In fs/fuse/dir.c (ffffffff8165966a)
Location: fs/fuse/fuse_i.h:882
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_tmpfile
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/file.c (ffffffff8165f225)
Location: fs/fuse/fuse_i.h:882
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_lock
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_writepage
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff816649d7)
Location: fs/fuse/fuse_i.h:882
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/acl.c (ffffffff816669ed)
Location: fs/fuse/fuse_i.h:882
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_inode_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8166778a)
Location: fs/fuse/fuse_i.h:882
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff81668c7d)
Location: fs/fuse/fuse_i.h:882
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff8166b445)
Location: fs/fuse/fuse_i.h:882
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
In fs/fuse/dir.c (ffffffff81693358)
Location: fs/fuse/fuse_i.h:909
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_get_attr
  - fs/fuse/dir.c:fuse_fillattr
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_tmpfile
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/file.c (ffffffff81699065)
Location: fs/fuse/fuse_i.h:909
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_lock
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_writepage
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8169eccc)
Location: fs/fuse/fuse_i.h:909
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/acl.c (ffffffff816a0cfd)
Location: fs/fuse/fuse_i.h:909
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_inode_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff816a1ada)
Location: fs/fuse/fuse_i.h:909
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff816a2f7d)
Location: fs/fuse/fuse_i.h:909
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff816a57c5)
Location: fs/fuse/fuse_i.h:909
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
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
In fs/fuse/dir.c (ffff800010508cf8)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffff8000105104b8)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffff800010510eb4)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/xattr.c (ffff800010514254)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffff8000105144f8)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffff800010515280)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:fuse_force_forget
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
In fs/fuse/dir.c (c06c4c78)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (c06cbc74)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_lk_fill
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (c06cc7b8)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/xattr.c (c06cf0d0)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (c06cf324)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (c06cff04)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
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
In fs/fuse/dir.c (c00000000064e7d0)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (c000000000657e34)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (c000000000658c40)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/xattr.c (c00000000065c508)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (c00000000065c84c)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (c00000000065d9f8)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:fuse_force_forget
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
In fs/fuse/dir.c (ffffffe000374870)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffe00037aca8)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffe00037b74e)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/xattr.c (ffffffe00037dd04)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
```
```
In fs/fuse/acl.c (ffffffe00037e0a6)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffe00037ec02)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_force_forget
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
In fs/fuse/dir.c (ffffffff8141db24)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81424ba2)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff81425696)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/xattr.c (ffffffff81427e92)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff814280b5)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff81428d3a)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_force_forget
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
In fs/fuse/dir.c (ffffffff8140e5a4)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81415622)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff81416116)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/xattr.c (ffffffff81418912)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff81418b35)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff814197ba)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_force_forget
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
In fs/fuse/dir.c (ffffffff81419cc4)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81420d42)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff81421836)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/xattr.c (ffffffff81424032)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff81424255)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff81424eda)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_force_forget
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
In fs/fuse/dir.c (ffffffff81430a34)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_dir_compat_ioctl
  - fs/fuse/dir.c:fuse_dir_ioctl
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81437b52)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff814386b6)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/xattr.c (ffffffff8143ae72)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff8143b095)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8143bd6f)
Location: fs/fuse/fuse_i.h:764
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_force_forget
```
</details>
</li>
</ul>

## Differences
