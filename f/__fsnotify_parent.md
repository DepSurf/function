# Function: <code>__fsnotify_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __fsnotify_parent(struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8124f850)
Location: fs/notify/fsnotify.c:89
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
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:d_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/file.c:fat_generic_ioctl
  - security/security.c:security_file_permission
  - security/security.c:security_file_open
```
**Symbols:**

```
ffffffff8124f850-ffffffff8124f925: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __fsnotify_parent(struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81277fa0)
Location: fs/notify/fsnotify.c:89
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
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:d_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_generic_ioctl
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff81277fa0-ffffffff81278076: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8128bc80)
Location: fs/notify/fsnotify.c:89
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
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:d_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_generic_ioctl
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff8128bc80-ffffffff8128bd56: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81298ab0)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:d_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_generic_ioctl
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff81298ab0-ffffffff81298bd0: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812bbe40)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:d_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_generic_ioctl
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff812bbe40-ffffffff812bbf60: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812e4a50)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:d_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_generic_ioctl
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff812e4a50-ffffffff812e4b74: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812f94c0)
Location: fs/notify/fsnotify.c:155
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
  - fs/readdir.c:iterate_dir
  - fs/dcache.c:d_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_generic_ioctl
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff812f94c0-ffffffff812f95e9: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81319b10)
Location: fs/notify/fsnotify.c:142
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff81319b10-ffffffff81319c45: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8132c940)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff8132c940-ffffffff8132ca75: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __fsnotify_parent(struct dentry *dentry, __u32 mask, const void *data, int data_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81373a20)
Location: fs/notify/fsnotify.c:180
Inline: False
Direct callers:
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
```
**Symbols:**

```
ffffffff81373a20-ffffffff81373cfe: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __fsnotify_parent(struct dentry *dentry, __u32 mask, const void *data, int data_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8137a3f0)
Location: fs/notify/fsnotify.c:180
Inline: False
Direct callers:
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff8137a3f0-ffffffff8137a6ce: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __fsnotify_parent(struct dentry *dentry, __u32 mask, const void *data, int data_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813c7070)
Location: fs/notify/fsnotify.c:180
Inline: False
Direct callers:
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff813c7070-ffffffff813c734e: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __fsnotify_parent(struct dentry *dentry, __u32 mask, const void *data, int data_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8144e3d0)
Location: fs/notify/fsnotify.c:178
Inline: False
Direct callers:
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - io_uring/io_uring.c:io_openat2
  - io_uring/io_uring.c:io_fallocate
  - io_uring/io_uring.c:__io_complete_rw_common
```
**Symbols:**

```
ffffffff8144e3d0-ffffffff8144e72e: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __fsnotify_parent(struct dentry *dentry, __u32 mask, const void *data, int data_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff814dcae0)
Location: fs/notify/fsnotify.c:178
Inline: False
Direct callers:
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - io_uring/sync.c:io_fallocate
  - io_uring/openclose.c:io_openat2
```
**Symbols:**

```
ffffffff814dcae0-ffffffff814dce3e: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __fsnotify_parent(struct dentry *dentry, __u32 mask, const void *data, int data_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81513330)
Location: fs/notify/fsnotify.c:178
Inline: False
Direct callers:
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/fat/file.c:fat_ioctl_set_attributes
  - io_uring/sync.c:io_fallocate
```
**Symbols:**

```
ffffffff81513330-ffffffff81513692: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __fsnotify_parent(struct dentry *dentry, __u32 mask, const void *data, int data_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff815477c0)
Location: fs/notify/fsnotify.c:178
Inline: False
Direct callers:
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
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - io_uring/sync.c:io_fallocate
```
**Symbols:**

```
ffffffff815477c0-ffffffff81547b22: __fsnotify_parent (STB_GLOBAL)
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
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffff8000103e82d0)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffff8000103e82d0-ffff8000103e8424: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (c05bfcbc)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
c05bfcbc-c05bfe18: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (c0000000004eec60)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
c0000000004eec60-c0000000004eee1c: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffe00029d012)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fat/file.c:fat_generic_ioctl
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffe00029d012-ffffffe00029d11c: __fsnotify_parent (STB_GLOBAL)
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
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81324f20)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff81324f20-ffffffff81325055: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81315ac0)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff81315ac0-ffffffff81315bf5: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813229f0)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff813229f0-ffffffff81322b25: __fsnotify_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __fsnotify_parent(const struct path *path, struct dentry *dentry, __u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81334740)
Location: fs/notify/fsnotify.c:146
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
**Symbols:**

```
ffffffff81334740-ffffffff81334875: __fsnotify_parent (STB_GLOBAL)
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
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
