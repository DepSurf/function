# Function: <code>fsnotify_parent</code>

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
In fs/open.c (ffffffff81209733)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_open
```
```
In fs/read_write.c (ffffffff8120c346)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
```
```
In fs/file_table.c (ffffffff8120e499)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812121cb)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
```
In fs/readdir.c (ffffffff8122045d)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff8122427d)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
```
```
In fs/attr.c (ffffffff81229849)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8123218c)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff812703c0)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/kernfs/file.c (ffffffff8128bf7c)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/fat/file.c (ffffffff812fb2a7)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In security/security.c (ffffffff8133ca50)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - security/security.c:security_file_permission
  - security/security.c:security_file_open
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
In fs/open.c (ffffffff8123151c)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81231ee4)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff81234eb9)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff81238c8f)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
```
In fs/readdir.c (ffffffff81247f48)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff8124c929)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
```
```
In fs/attr.c (ffffffff81251f4c)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8125ae21)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff8129bc01)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff8132efa5)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In security/security.c (ffffffff81373775)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff81243ad9)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812452a6)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff81247a6d)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff8124b945)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
```
In fs/readdir.c (ffffffff8125af8c)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff8125f919)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
```
```
In fs/attr.c (ffffffff81265181)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8126e6ec)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff812b07ca)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff81344cf8)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In security/security.c (ffffffff8138a0aa)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff8124f2f8)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81250771)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff8125329d)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff81257a8e)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
```
In fs/readdir.c (ffffffff8126798a)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff8126d269)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
```
```
In fs/attr.c (ffffffff812729aa)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8127bede)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff812bdc58)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff81359753)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In security/security.c (ffffffff8139f4aa)
Location: include/linux/fsnotify.h:20
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff81271278)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81272637)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff8127539d)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff81279d61)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
```
In fs/readdir.c (ffffffff8128a20c)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff8128f611)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
```
```
In fs/attr.c (ffffffff812952d0)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8129e97e)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff812e1348)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff8137e463)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In security/security.c (ffffffff813c5020)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff81296eb1)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81298666)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff8129bd2a)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812a0943)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812b064a)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff812b4e89)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
```
```
In fs/attr.c (ffffffff812bb4c1)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff812c565a)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff8130d59d)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff813ace97)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In security/security.c (ffffffff813f526b)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff812abb64)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812ace15)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812b09e0)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812b590d)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812c57ab)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff812ca0e9)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
```
```
In fs/attr.c (ffffffff812d06b2)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff812da85a)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff8132319e)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff813c623d)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In security/security.c (ffffffff814106a6)
Location: include/linux/fsnotify.h:21
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff812c836d)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812c9833)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812cd364)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812d26e7)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812e222d)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff812ed6e4)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff812f8dd9)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff8134ab91)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff813f0bd6)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff8143de5d)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff812d9d7d)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812dda20)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812ded84)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812e41f7)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812f3cfd)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff812ff1a1)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8130aa09)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff81362d79)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff8140aab6)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff81457906)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fsnotify_parent(struct dentry *dentry, __u32 mask, const void *data, int data_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813668b0)
Location: fs/notify/fsnotify.c:146
Inline: True
Direct callers:
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
  - fs/readdir.c:iterate_dir
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/io_uring.c:io_openat2
  - fs/fhandle.c:do_handle_open
  - fs/fat/file.c:fat_ioctl_set_attributes
  - security/security.c:security_file_open
  - security/security.c:security_file_open
```
**Symbols:**

```
ffffffff813668b0-ffffffff813669ad: fsnotify_parent (STB_GLOBAL)
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
In fs/open.c (ffffffff8131bd43)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81320a58)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
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
```
```
In fs/file_table.c (ffffffff8132141c)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff81328205)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/readdir.c (ffffffff813379cd)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff81343bf2)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8134faa1)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/remap_range.c (ffffffff81366651)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/io_uring.c (ffffffff813928a5)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff813b9d69)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff81474ad0)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff814c7d6a)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
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
In fs/open.c (ffffffff81321eb3)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81326b08)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
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
```
```
In fs/file_table.c (ffffffff813271bc)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff8132e129)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/readdir.c (ffffffff8133e12d)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff81349f6a)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff813565c9)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/remap_range.c (ffffffff8136cefa)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/io_uring.c (ffffffff81396179)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff813c0ec9)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff8147a47e)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff814ce39d)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff8136f38f)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813740a4)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
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
```
```
In fs/file_table.c (ffffffff81374a47)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff8137b918)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/readdir.c (ffffffff8138baad)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff81397d01)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff813a4b09)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/remap_range.c (ffffffff813bbbb6)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/io_uring.c (ffffffff813eb13b)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff81410f80)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff814d1ade)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff815256ab)
Location: include/linux/fsnotify.h:57
Inline: True
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
In fs/open.c (ffffffff813eddc2)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813f2ec1)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
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
```
```
In fs/file_table.c (ffffffff813f3842)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff813fc1b2)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/readdir.c (ffffffff8140d00a)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff81419e24)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81428660)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/remap_range.c (ffffffff81442456)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/fhandle.c (ffffffff8148695f)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff8155e75d)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff815b983c)
Location: include/linux/fsnotify.h:57
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816d42e8)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_openat2
  - io_uring/io_uring.c:io_fallocate
  - io_uring/io_uring.c:__io_complete_rw_common
  - io_uring/io_uring.c:__io_complete_rw_common
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
In fs/open.c (ffffffff81476542)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff8147bcd5)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
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
```
```
In fs/file_table.c (ffffffff8147c616)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff81485c22)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/readdir.c (ffffffff81497aaa)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff814a5e99)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff814b5b80)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/remap_range.c (ffffffff814d1136)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/posix_acl.c (ffffffff81516078)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/fhandle.c (ffffffff8151a2bf)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff81600953)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff816650fc)
Location: include/linux/fsnotify.h:57
Inline: True
```
```
In io_uring/sync.c (ffffffff81793cb9)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/openclose.c (ffffffff817947d8)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - io_uring/openclose.c:io_openat2
```
```
In io_uring/rw.c (ffffffff817a3a0f)
Location: include/linux/fsnotify.h:57
Inline: True
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
In fs/open.c (ffffffff814a8814)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814b0892)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
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
```
```
In fs/file_table.c (ffffffff814b10c5)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/readdir.c (ffffffff814cca9a)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff814dae4a)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff814ea3d0)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/splice.c (ffffffff814fdec8)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff815073c1)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/posix_acl.c (ffffffff8154da0f)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/fat/file.c (ffffffff81638846)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff8169d624)
Location: include/linux/fsnotify.h:57
Inline: True
```
```
In io_uring/sync.c (ffffffff817d49eb)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/rw.c (ffffffff817e4a57)
Location: include/linux/fsnotify.h:57
Inline: True
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
In fs/open.c (ffffffff814d9900)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814e2035)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
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
```
```
In fs/file_table.c (ffffffff814e2a08)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/readdir.c (ffffffff814ff5d6)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff8150d3fc)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8151e270)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/splice.c (ffffffff81532aa1)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8153c870)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/posix_acl.c (ffffffff8158383f)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/fat/file.c (ffffffff81671d36)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff816dcaf0)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
```
```
In io_uring/sync.c (ffffffff8181884c)
Location: include/linux/fsnotify.h:57
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/rw.c (ffffffff81828efd)
Location: include/linux/fsnotify.h:57
Inline: True
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
In fs/open.c (ffff80001037f10c)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffff800010383934)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffff800010385568)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffff80001038d0ac)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__arm64_sys_uselib
```
```
In fs/readdir.c (ffff80001039f304)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffff8000103b05e4)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffff8000103bece8)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffff8000104295b0)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffff8000104eafa4)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffff800010543594)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
In fs/open.c (c05699e8)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (c056b0f4)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (c056e330)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (c05739b0)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
```
In fs/readdir.c (c0584150)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (c058ffa0)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (c059baf0)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (c05f2358)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In fs/fat/file.c (c06a8f9c)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (c06f9508)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
In fs/open.c (c000000000475038)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (c000000000479d68)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (c00000000047b538)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (c0000000004833ec)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
```
In fs/readdir.c (c000000000499aa0)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (c0000000004abf84)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (c0000000004bd030)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (c000000000539ae8)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (c000000000629320)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (c00000000069763c)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffe000254cdc)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffe00025722c)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffe000258264)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffe00025d19a)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
```
In fs/readdir.c (ffffffe00026a154)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffe0002749b2)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffe00027f668)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffe0002c75bc)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In fs/fat/file.c (ffffffe00035bd16)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In security/security.c (ffffffe00039faaa)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff812d235d)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812d6000)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812d7364)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812dc7d7)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812ec2dd)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff812f7781)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81302fe9)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff8135b359)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff81403096)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff8144fee6)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff812c2fdd)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812c6c80)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812c7fe4)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812cd457)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812dcf0d)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff812e83a1)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff812f3c09)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff8134bff9)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff813f3b16)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff81440936)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff812d016d)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812d3e10)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812d5174)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812da5e7)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812ea0ed)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff812f5591)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81300dd9)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff81358e29)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff81400416)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff8144bf86)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
In fs/open.c (ffffffff812e0f7d)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812e4c70)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812e5fc3)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812eb496)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812fb0dd)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/attr.c (ffffffff81306721)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81312119)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fhandle.c (ffffffff8136c529)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/fat/file.c (ffffffff81416046)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/security.c (ffffffff81463356)
Location: include/linux/fsnotify.h:34
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
