# Function: <code>fsnotify_file</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130fa7a)
Location: include/linux/fsnotify.h:62
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81311e22)
Location: include/linux/fsnotify.h:62
Inline: True
Inline callers:
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
```
```
In fs/file_table.c (ffffffff81315d6e)
Location: include/linux/fsnotify.h:62
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff8131c6aa)
Location: include/linux/fsnotify.h:62
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/readdir.c (ffffffff8132c3c2)
Location: include/linux/fsnotify.h:62
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/io_uring.c (ffffffff81384090)
Location: include/linux/fsnotify.h:62
Inline: True
Inline callers:
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff813a89f7)
Location: include/linux/fsnotify.h:62
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff814aa75a)
Location: include/linux/fsnotify.h:62
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
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
In fs/open.c (ffffffff8131bd34)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81320a4a)
Location: include/linux/fsnotify.h:83
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
In fs/file_table.c (ffffffff8132132d)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff813281f3)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/readdir.c (ffffffff813379c2)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/remap_range.c (ffffffff81366642)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/io_uring.c (ffffffff81392873)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff813b9d41)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff814c7d28)
Location: include/linux/fsnotify.h:83
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
In fs/open.c (ffffffff81321ea4)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81326af9)
Location: include/linux/fsnotify.h:83
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
In fs/file_table.c (ffffffff813270cd)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff8132e117)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/readdir.c (ffffffff8133e122)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/remap_range.c (ffffffff8136ceeb)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/io_uring.c (ffffffff8139616a)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff813c0ea1)
Location: include/linux/fsnotify.h:83
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff814ce35c)
Location: include/linux/fsnotify.h:83
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
In fs/open.c (ffffffff8136f384)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81374099)
Location: include/linux/fsnotify.h:92
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
In fs/file_table.c (ffffffff8137495d)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff8137b90b)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/readdir.c (ffffffff8138baa2)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/remap_range.c (ffffffff813bbbab)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/io_uring.c (ffffffff813eb130)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff81410f5c)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff815256a0)
Location: include/linux/fsnotify.h:92
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
In fs/open.c (ffffffff813eddb5)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813f2eb4)
Location: include/linux/fsnotify.h:92
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
In fs/file_table.c (ffffffff813f374a)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff813fc1a5)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/readdir.c (ffffffff8140cfff)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/remap_range.c (ffffffff8144244b)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/fhandle.c (ffffffff81486939)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff815b9831)
Location: include/linux/fsnotify.h:92
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816d42dd)
Location: include/linux/fsnotify.h:92
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
In fs/open.c (ffffffff81476535)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff8147bb55)
Location: include/linux/fsnotify.h:92
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
In fs/file_table.c (ffffffff8147c51a)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff81485c15)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/readdir.c (ffffffff81497a9f)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/remap_range.c (ffffffff814d112b)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/fhandle.c (ffffffff8151a299)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff816650f1)
Location: include/linux/fsnotify.h:92
Inline: True
```
```
In io_uring/sync.c (ffffffff81793caf)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/openclose.c (ffffffff817947cd)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - io_uring/openclose.c:io_openat2
```
```
In io_uring/rw.c (ffffffff817a39e8)
Location: include/linux/fsnotify.h:92
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
In fs/open.c (ffffffff814a875b)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814b06e1)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
```
```
In fs/file_table.c (ffffffff814b10a3)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/readdir.c (ffffffff814cca77)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff814fdea7)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff815073a0)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In security/security.c (ffffffff8169d60b)
Location: include/linux/fsnotify.h:92
Inline: True
```
```
In io_uring/sync.c (ffffffff817d49cf)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/rw.c (ffffffff817e4a18)
Location: include/linux/fsnotify.h:92
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
In fs/open.c (ffffffff814d9838)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814e2025)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_iter_read
  - fs/read_write.c:vfs_iter_read
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/file_table.c (ffffffff814e28d3)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/readdir.c (ffffffff814ff5c9)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff81532a8d)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8153c767)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In security/security.c (ffffffff816dcac2)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
```
```
In io_uring/sync.c (ffffffff8181883f)
Location: include/linux/fsnotify.h:92
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/rw.c (ffffffff81828ef0)
Location: include/linux/fsnotify.h:92
Inline: True
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
