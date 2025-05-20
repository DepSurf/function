# Function: <code>fsnotify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, void *data, int data_is, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8124f290)
Location: fs/notify/fsnotify.c:190
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_open
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_generic_ioctl
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_permission
  - security/security.c:security_file_open
```
**Symbols:**

```
ffffffff8124f290-ffffffff8124f72d: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, void *data, int data_is, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812779f0)
Location: fs/notify/fsnotify.c:190
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_generic_ioctl
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff812779f0-ffffffff81277e77: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8128b6d0)
Location: fs/notify/fsnotify.c:190
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_generic_ioctl
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff8128b6d0-ffffffff8128bb57: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812984d0)
Location: fs/notify/fsnotify.c:252
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_generic_ioctl
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff812984d0-ffffffff81298997: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812bb7d0)
Location: fs/notify/fsnotify.c:275
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_generic_ioctl
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff812bb7d0-ffffffff812bbd30: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812e4370)
Location: fs/notify/fsnotify.c:318
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_generic_ioctl
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff812e4370-ffffffff812e493f: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812f8ff0)
Location: fs/notify/fsnotify.c:327
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_generic_ioctl
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff812f8ff0-ffffffff812f93a3: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81319630)
Location: fs/notify/fsnotify.c:314
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff81319630-ffffffff813199f8: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8132c460)
Location: fs/notify/fsnotify.c:318
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff8132c460-ffffffff8132c828: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813663c0)
Location: fs/notify/fsnotify.c:311
Inline: False
Direct callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
```
**Symbols:**

```
ffffffff813663c0-ffffffff813665ec: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fsnotify(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, struct inode *inode, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81373460)
Location: fs/notify/fsnotify.c:462
Inline: False
Direct callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
```
**Symbols:**

```
ffffffff81373460-ffffffff81373748: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fsnotify(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, struct inode *inode, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81379d40)
Location: fs/notify/fsnotify.c:462
Inline: False
Direct callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff81379d40-ffffffff8137a0ab: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fsnotify(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, struct inode *inode, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813c6930)
Location: fs/notify/fsnotify.c:462
Inline: False
Direct callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/libfs.c:simple_recursive_removal
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff813c6930-ffffffff813c6d3a: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fsnotify(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, struct inode *inode, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8144d9e0)
Location: fs/notify/fsnotify.c:478
Inline: False
Direct callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/libfs.c:simple_recursive_removal
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - io_uring/io_uring.c:io_openat2
  - io_uring/io_uring.c:io_fallocate
  - io_uring/io_uring.c:__io_complete_rw_common
```
**Symbols:**

```
ffffffff8144d9e0-ffffffff8144e075: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fsnotify(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, struct inode *inode, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff814dc0a0)
Location: fs/notify/fsnotify.c:481
Inline: False
Direct callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/libfs.c:simple_recursive_removal
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - io_uring/sync.c:io_fallocate
  - io_uring/openclose.c:io_openat2
```
**Symbols:**

```
ffffffff814dc0a0-ffffffff814dc742: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fsnotify(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, struct inode *inode, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81512890)
Location: fs/notify/fsnotify.c:481
Inline: False
Direct callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/file_table.c:__fput
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/libfs.c:simple_recursive_removal
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - io_uring/sync.c:io_fallocate
```
**Symbols:**

```
ffffffff81512890-ffffffff81512f92: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fsnotify(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, struct inode *inode, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81546d40)
Location: fs/notify/fsnotify.c:481
Inline: False
Direct callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_iter_read
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:rw_verify_area
  - fs/file_table.c:__fput
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/libfs.c:simple_recursive_removal
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - io_uring/sync.c:io_fallocate
```
**Symbols:**

```
ffffffff81546d40-ffffffff81547442: fsnotify (STB_GLOBAL)
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
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffff8000103e7d48)
Location: fs/notify/fsnotify.c:318
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__arm64_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffff8000103e7d48-ffff8000103e8118: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (c05bf890)
Location: fs/notify/fsnotify.c:318
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
c05bf890-c05bfcbc: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (c0000000004ee740)
Location: fs/notify/fsnotify.c:318
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
c0000000004ee740-c0000000004eec5c: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffe00029cb4c)
Location: fs/notify/fsnotify.c:318
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_generic_ioctl
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffe00029cb4c-ffffffe00029ce6a: fsnotify (STB_GLOBAL)
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
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81324a40)
Location: fs/notify/fsnotify.c:318
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff81324a40-ffffffff81324e08: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813155e0)
Location: fs/notify/fsnotify.c:318
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff813155e0-ffffffff813159a8: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81322510)
Location: fs/notify/fsnotify.c:318
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff81322510-ffffffff813228d8: fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fsnotify(struct inode *to_tell, __u32 mask, const void *data, int data_is, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81334370)
Location: fs/notify/fsnotify.c:318
Inline: False
Direct callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/file_table.c:__fput
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:dentry_unlink_inode
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff81334370-ffffffff81334738: fsnotify (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *data</code> ➡️ <code>const void *data</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char *file_name</code> ➡️ <code>const struct qstr *file_name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int data_type</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode *dir</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *to_tell</code>
</li>
<li>
<b>Param removed. </b>
<code>int data_is</code>
</li>
<li>
<b>Param reordered. </b>
<code>to_tell, mask, data, data_is, file_name, cookie</code> ➡️ <code>mask, data, data_type, dir, file_name, inode, cookie</code>
</li>
</ul>
</details>
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
