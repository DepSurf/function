# Function: <code>fsnotify_access</code>

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
In fs/read_write.c (ffffffff8120c783)
Location: include/linux/fsnotify.h:194
Inline: True
Inline callers:
  - fs/read_write.c:vfs_read
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_sendfile
```
```
In fs/readdir.c (ffffffff8122041d)
Location: include/linux/fsnotify.h:194
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff81231ebd)
Location: include/linux/fsnotify.h:173
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
```
```
In fs/readdir.c (ffffffff81247f1e)
Location: include/linux/fsnotify.h:173
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff81245278)
Location: include/linux/fsnotify.h:177
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
```
```
In fs/readdir.c (ffffffff8125af5a)
Location: include/linux/fsnotify.h:177
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff812506d6)
Location: include/linux/fsnotify.h:177
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffffffff81267958)
Location: include/linux/fsnotify.h:177
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff8127259c)
Location: include/linux/fsnotify.h:178
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffffffff8128a1ce)
Location: include/linux/fsnotify.h:178
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff812985cb)
Location: include/linux/fsnotify.h:178
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffffffff812b05a8)
Location: include/linux/fsnotify.h:178
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff812acd73)
Location: include/linux/fsnotify.h:190
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffffffff812c5707)
Location: include/linux/fsnotify.h:190
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff812c9792)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffffffff812e2187)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff812dd948)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffffffff812f3c57)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff81311e22)
Location: include/linux/fsnotify.h:247
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/readdir.c (ffffffff8132c3c2)
Location: include/linux/fsnotify.h:247
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff81320a4a)
Location: include/linux/fsnotify.h:245
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/readdir.c (ffffffff813379c2)
Location: include/linux/fsnotify.h:245
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/remap_range.c (ffffffff81366642)
Location: include/linux/fsnotify.h:245
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
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
In fs/read_write.c (ffffffff81326af9)
Location: include/linux/fsnotify.h:245
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/readdir.c (ffffffff8133e122)
Location: include/linux/fsnotify.h:245
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/remap_range.c (ffffffff8136ceeb)
Location: include/linux/fsnotify.h:245
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
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
In fs/read_write.c (ffffffff81374099)
Location: include/linux/fsnotify.h:290
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/readdir.c (ffffffff8138baa2)
Location: include/linux/fsnotify.h:290
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/remap_range.c (ffffffff813bbbab)
Location: include/linux/fsnotify.h:290
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
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
In fs/read_write.c (ffffffff813f2eb4)
Location: include/linux/fsnotify.h:307
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/readdir.c (ffffffff8140cfff)
Location: include/linux/fsnotify.h:307
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/remap_range.c (ffffffff8144244b)
Location: include/linux/fsnotify.h:307
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
```
```
In io_uring/io_uring.c (ffffffff816cc3dc)
Location: include/linux/fsnotify.h:307
Inline: True
Inline callers:
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
In fs/read_write.c (ffffffff8147bb55)
Location: include/linux/fsnotify.h:307
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/readdir.c (ffffffff81497a9f)
Location: include/linux/fsnotify.h:307
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/remap_range.c (ffffffff814d112b)
Location: include/linux/fsnotify.h:307
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
```
```
In io_uring/rw.c (ffffffff817a3a8a)
Location: include/linux/fsnotify.h:307
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
In fs/read_write.c (ffffffff814b06e1)
Location: include/linux/fsnotify.h:309
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/readdir.c (ffffffff814cca77)
Location: include/linux/fsnotify.h:309
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff814fdea7)
Location: include/linux/fsnotify.h:309
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff815073a0)
Location: include/linux/fsnotify.h:309
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
```
```
In io_uring/rw.c (ffffffff817e4ad6)
Location: include/linux/fsnotify.h:309
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
In fs/read_write.c (ffffffff814e2025)
Location: include/linux/fsnotify.h:347
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/readdir.c (ffffffff814ff67f)
Location: include/linux/fsnotify.h:347
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/splice.c (ffffffff81532a8d)
Location: include/linux/fsnotify.h:347
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8153c767)
Location: include/linux/fsnotify.h:347
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In io_uring/rw.c (ffffffff81828f62)
Location: include/linux/fsnotify.h:347
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
In fs/read_write.c (ffff80001038384c)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffff80001039f240)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (c056b030)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (c05840bc)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (c000000000479c10)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (c000000000499950)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffe000257174)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffffffe00026a0b0)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff812d5f28)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffffffff812ec237)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff812c6ba8)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffffffff812dce67)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff812d3d38)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffffffff812ea047)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
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
In fs/read_write.c (ffffffff812e4b98)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
```
```
In fs/readdir.c (ffffffff812fb037)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
</details>
</li>
</ul>

## Differences
