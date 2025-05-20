# Function: <code>fsnotify_path</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812abb64)
Location: include/linux/fsnotify.h:33
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812ace15)
Location: include/linux/fsnotify.h:33
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812b09e0)
Location: include/linux/fsnotify.h:33
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812b590d)
Location: include/linux/fsnotify.h:33
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812c57ab)
Location: include/linux/fsnotify.h:33
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/fhandle.c (ffffffff8132319e)
Location: include/linux/fsnotify.h:33
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff814106a6)
Location: include/linux/fsnotify.h:33
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812c9833)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812cd364)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812d26e7)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812e222d)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/fhandle.c (ffffffff8134ab91)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff8143de5d)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812dda20)
Location: include/linux/fsnotify.h:47
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
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812ded84)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812e41f7)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812f3cfd)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/fhandle.c (ffffffff81362d79)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff81457906)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffff800010383934)
Location: include/linux/fsnotify.h:47
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
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffff800010385568)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffff80001038d0ac)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__arm64_sys_uselib
```
```
In fs/readdir.c (ffff80001039f304)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/fhandle.c (ffff8000104295b0)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffff800010543594)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (c056b0f4)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (c056e330)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (c05739b0)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
```
In fs/readdir.c (c0584150)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/fhandle.c (c05f2358)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In security/security.c (c06f9508)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (c000000000479d68)
Location: include/linux/fsnotify.h:47
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
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (c00000000047b538)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (c0000000004833ec)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
```
In fs/readdir.c (c000000000499aa0)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/fhandle.c (c000000000539ae8)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (c00000000069763c)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffe00025722c)
Location: include/linux/fsnotify.h:47
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
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffe000258264)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffe00025d19a)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
```
In fs/readdir.c (ffffffe00026a154)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/fhandle.c (ffffffe0002c75bc)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In security/security.c (ffffffe00039faaa)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812d6000)
Location: include/linux/fsnotify.h:47
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
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812d7364)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812dc7d7)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812ec2dd)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/fhandle.c (ffffffff8135b359)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff8144fee6)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812c6c80)
Location: include/linux/fsnotify.h:47
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
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812c7fe4)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812cd457)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812dcf0d)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/fhandle.c (ffffffff8134bff9)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff81440936)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812d3e10)
Location: include/linux/fsnotify.h:47
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
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812d5174)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812da5e7)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812ea0ed)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/fhandle.c (ffffffff81358e29)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff8144bf86)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
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
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:do_sys_open
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812e4c70)
Location: include/linux/fsnotify.h:47
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
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
```
In fs/file_table.c (ffffffff812e5fc3)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff812eb496)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/readdir.c (ffffffff812fb0dd)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/fhandle.c (ffffffff8136c529)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In security/security.c (ffffffff81463356)
Location: include/linux/fsnotify.h:47
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_open
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
  - security/security.c:security_file_permission
```
</details>
</li>
</ul>

## Differences
