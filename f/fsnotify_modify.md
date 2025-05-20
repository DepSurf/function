# Function: <code>fsnotify_modify</code>

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
In fs/open.c (ffffffff8120970c)
Location: include/linux/fsnotify.h:212
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff8120c2f2)
Location: include/linux/fsnotify.h:212
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_sendfile
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
In fs/open.c (ffffffff8122f4fc)
Location: include/linux/fsnotify.h:191
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81231f18)
Location: include/linux/fsnotify.h:191
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff81241a5d)
Location: include/linux/fsnotify.h:195
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812452d2)
Location: include/linux/fsnotify.h:195
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff8124cdbc)
Location: include/linux/fsnotify.h:195
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81250700)
Location: include/linux/fsnotify.h:195
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff8126ed2e)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812725c6)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff81294914)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812985f5)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff812a98e2)
Location: include/linux/fsnotify.h:206
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812acd9a)
Location: include/linux/fsnotify.h:206
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff812c607b)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812c97b9)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff812d7a8b)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812dd982)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff8130dcad)
Location: include/linux/fsnotify.h:255
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81311e62)
Location: include/linux/fsnotify.h:255
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff81319fad)
Location: include/linux/fsnotify.h:253
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81320a9e)
Location: include/linux/fsnotify.h:253
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
```
```
In fs/remap_range.c (ffffffff81366687)
Location: include/linux/fsnotify.h:253
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
In fs/open.c (ffffffff8132008d)
Location: include/linux/fsnotify.h:253
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81326b4e)
Location: include/linux/fsnotify.h:253
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
```
```
In fs/remap_range.c (ffffffff8136cf30)
Location: include/linux/fsnotify.h:253
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
In fs/open.c (ffffffff8136d62d)
Location: include/linux/fsnotify.h:298
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813740fe)
Location: include/linux/fsnotify.h:298
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
```
```
In fs/remap_range.c (ffffffff813bbc00)
Location: include/linux/fsnotify.h:298
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
In fs/open.c (ffffffff813ec1e0)
Location: include/linux/fsnotify.h:315
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813f2f24)
Location: include/linux/fsnotify.h:315
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
```
```
In fs/remap_range.c (ffffffff814424a0)
Location: include/linux/fsnotify.h:315
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
```
```
In io_uring/io_uring.c (ffffffff816d051d)
Location: include/linux/fsnotify.h:315
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fallocate
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
In fs/open.c (ffffffff814746b0)
Location: include/linux/fsnotify.h:315
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff8147bb71)
Location: include/linux/fsnotify.h:315
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
```
```
In fs/remap_range.c (ffffffff814d1180)
Location: include/linux/fsnotify.h:315
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
```
```
In io_uring/sync.c (ffffffff81793caf)
Location: include/linux/fsnotify.h:315
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/rw.c (ffffffff817a39e8)
Location: include/linux/fsnotify.h:315
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
In fs/open.c (ffffffff814a907a)
Location: include/linux/fsnotify.h:317
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814b0701)
Location: include/linux/fsnotify.h:317
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
```
```
In fs/splice.c (ffffffff814fdf0e)
Location: include/linux/fsnotify.h:317
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8150740f)
Location: include/linux/fsnotify.h:317
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
```
```
In io_uring/sync.c (ffffffff817d49cf)
Location: include/linux/fsnotify.h:317
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/rw.c (ffffffff817e4a18)
Location: include/linux/fsnotify.h:317
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
In fs/open.c (ffffffff814da0d9)
Location: include/linux/fsnotify.h:355
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814e209b)
Location: include/linux/fsnotify.h:355
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
```
```
In fs/splice.c (ffffffff81532af7)
Location: include/linux/fsnotify.h:355
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8153c772)
Location: include/linux/fsnotify.h:355
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In io_uring/sync.c (ffffffff8181883f)
Location: include/linux/fsnotify.h:355
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/rw.c (ffffffff81828ef0)
Location: include/linux/fsnotify.h:355
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
In fs/open.c (ffff80001037cebc)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffff800010383898)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (c0567b80)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (c056b054)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (c0000000004722f0)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (c000000000479c58)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffe00025334a)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffe0002571a2)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff812d006b)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812d5f62)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff812c0ceb)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812c6be2)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff812cde7b)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812d3d72)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
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
In fs/open.c (ffffffff812dec8b)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812e4bd2)
Location: include/linux/fsnotify.h:246
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:__kernel_write
```
</details>
</li>
</ul>

## Differences
