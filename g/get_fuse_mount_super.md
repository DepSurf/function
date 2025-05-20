# Function: <code>get_fuse_mount_super</code>

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
In <code>5.8</code>: Absent ⚠️
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
Location: fs/fuse/fuse_i.h:824
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
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_settime
```
```
In fs/fuse/file.c (ffffffff814918bd)
Location: fs/fuse/fuse_i.h:824
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_compat_ioctl
  - fs/fuse/file.c:fuse_file_ioctl
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_file_lock
  - fs/fuse/file.c:fuse_setlk
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
In fs/fuse/inode.c (ffffffff814998ef)
Location: fs/fuse/fuse_i.h:824
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_show_options
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff8149abeb)
Location: fs/fuse/fuse_i.h:824
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff8149b005)
Location: fs/fuse/fuse_i.h:824
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8149ba37)
Location: fs/fuse/fuse_i.h:824
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/dax.c (ffffffff8149e1c5)
Location: fs/fuse/fuse_i.h:824
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
Location: fs/fuse/fuse_i.h:833
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
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814961cf)
Location: fs/fuse/fuse_i.h:833
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_file_lock
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
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
In fs/fuse/inode.c (ffffffff8149eb1f)
Location: fs/fuse/fuse_i.h:833
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_show_options
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff8149fe3b)
Location: fs/fuse/fuse_i.h:833
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff814a0255)
Location: fs/fuse/fuse_i.h:833
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff814a0b57)
Location: fs/fuse/fuse_i.h:833
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff814a21a5)
Location: fs/fuse/fuse_i.h:833
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff814a4195)
Location: fs/fuse/fuse_i.h:833
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
Location: fs/fuse/fuse_i.h:838
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
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814edc8f)
Location: fs/fuse/fuse_i.h:838
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_file_lock
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
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
In fs/fuse/inode.c (ffffffff814f4f14)
Location: fs/fuse/fuse_i.h:838
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_test_super
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_show_options
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff814f7e4b)
Location: fs/fuse/fuse_i.h:838
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff814f8275)
Location: fs/fuse/fuse_i.h:838
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff814f8a24)
Location: fs/fuse/fuse_i.h:838
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff814fa245)
Location: fs/fuse/fuse_i.h:838
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff814fc235)
Location: fs/fuse/fuse_i.h:838
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
Location: fs/fuse/fuse_i.h:859
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
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8157d03f)
Location: fs/fuse/fuse_i.h:859
Inline: True
Inline callers:
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
  - fs/fuse/file.c:fuse_writepage
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_attr
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
In fs/fuse/inode.c (ffffffff81584e34)
Location: fs/fuse/fuse_i.h:859
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_test_super
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_show_options
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff81587e9b)
Location: fs/fuse/fuse_i.h:859
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff81588315)
Location: fs/fuse/fuse_i.h:859
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff81589004)
Location: fs/fuse/fuse_i.h:859
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff8158a504)
Location: fs/fuse/fuse_i.h:859
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff8158c865)
Location: fs/fuse/fuse_i.h:859
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
Location: fs/fuse/fuse_i.h:862
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
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_tmpfile
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81622b7f)
Location: fs/fuse/fuse_i.h:862
Inline: True
Inline callers:
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
  - fs/fuse/file.c:fuse_writepage
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8162afc4)
Location: fs/fuse/fuse_i.h:862
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_test_super
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_show_options
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff8162e1fb)
Location: fs/fuse/fuse_i.h:862
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff8162e7b1)
Location: fs/fuse/fuse_i.h:862
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_inode_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8162f517)
Location: fs/fuse/fuse_i.h:862
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff8162fdf5)
Location: fs/fuse/fuse_i.h:862
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff81633155)
Location: fs/fuse/fuse_i.h:862
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
Location: fs/fuse/fuse_i.h:867
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
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_tmpfile
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8165afbf)
Location: fs/fuse/fuse_i.h:867
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
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
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff816631e4)
Location: fs/fuse/fuse_i.h:867
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_test_super
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_show_options
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff8166643b)
Location: fs/fuse/fuse_i.h:867
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff816669f1)
Location: fs/fuse/fuse_i.h:867
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_inode_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8166778a)
Location: fs/fuse/fuse_i.h:867
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff81667ff5)
Location: fs/fuse/fuse_i.h:867
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff8166b445)
Location: fs/fuse/fuse_i.h:867
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
Location: fs/fuse/fuse_i.h:894
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
  - fs/fuse/dir.c:fuse_update_get_attr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_statx
  - fs/fuse/dir.c:fuse_fillattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_tmpfile
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81694c8f)
Location: fs/fuse/fuse_i.h:894
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
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
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8169d354)
Location: fs/fuse/fuse_i.h:894
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_test_super
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_show_options
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/inode.c:fuse_lock_inode
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff816a071b)
Location: fs/fuse/fuse_i.h:894
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/acl.c (ffffffff816a0d01)
Location: fs/fuse/fuse_i.h:894
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_inode_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff816a1ada)
Location: fs/fuse/fuse_i.h:894
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff816a22f5)
Location: fs/fuse/fuse_i.h:894
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
```
In fs/fuse/dax.c (ffffffff816a57c5)
Location: fs/fuse/fuse_i.h:894
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_dontcache
  - fs/fuse/dax.c:fuse_dax_inode_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_writepages
  - fs/fuse/dax.c:fuse_iomap_begin
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
