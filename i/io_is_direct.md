# Function: <code>io_is_direct</code>

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
In mm/page_io.c (ffffffff811d22de)
Location: include/linux/fs.h:2877
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8120be7b)
Location: include/linux/fs.h:2877
Inline: True
```
```
In fs/aio.c (ffffffff8125d610)
Location: include/linux/fs.h:2877
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In drivers/block/loop.c (ffffffff8156fa27)
Location: include/linux/fs.h:2877
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_switch
  - drivers/block/loop.c:lo_ioctl
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
In mm/page_io.c (ffffffff811efeb4)
Location: include/linux/fs.h:3022
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8123195f)
Location: include/linux/fs.h:3022
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff812862fa)
Location: include/linux/fs.h:3022
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In drivers/block/loop.c (ffffffff815c5908)
Location: include/linux/fs.h:3022
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_switch
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
In mm/page_io.c (ffffffff812007f0)
Location: include/linux/fs.h:2992
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81243f0f)
Location: include/linux/fs.h:2992
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff81279038)
Location: include/linux/fs.h:2992
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8129971e)
Location: include/linux/fs.h:2992
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In drivers/block/loop.c (ffffffff815f3c8f)
Location: include/linux/fs.h:2992
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
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
In mm/page_io.c (ffffffff8120b42a)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8124f8b2)
Location: include/linux/fs.h:3138
Inline: True
```
```
In fs/splice.c (ffffffff81286598)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812a7402)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In drivers/block/loop.c (ffffffff8160848b)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_switch
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
In mm/page_io.c (ffffffff812248ea)
Location: include/linux/fs.h:3204
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812717f2)
Location: include/linux/fs.h:3204
Inline: True
```
```
In fs/splice.c (ffffffff812a9098)
Location: include/linux/fs.h:3204
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812ca797)
Location: include/linux/fs.h:3204
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:3204
Inline: True
```
```
In drivers/block/loop.c (ffffffff81670d73)
Location: include/linux/fs.h:3204
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
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
In mm/page_io.c (ffffffff81246f74)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81297642)
Location: include/linux/fs.h:3229
Inline: True
```
```
In fs/splice.c (ffffffff812cfbc8)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812f26a0)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/fuse/file.c (ffffffff813caea5)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_readpage
```
```
In drivers/block/loop.c (ffffffff816ac05a)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
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
In mm/page_io.c (ffffffff8125b3ab)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812ac2f2)
Location: include/linux/fs.h:3308
Inline: True
```
```
In fs/splice.c (ffffffff812e4fb5)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8130708e)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:3308
Inline: True
```
```
In drivers/block/loop.c (ffffffff816ce1cf)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
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
In mm/page_io.c (ffffffff812764f9)
Location: include/linux/fs.h:3319
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c89ed)
Location: include/linux/fs.h:3319
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff813037a5)
Location: include/linux/fs.h:3319
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8132865e)
Location: include/linux/fs.h:3319
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8132d63b)
Location: include/linux/fs.h:3319
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:3319
Inline: True
```
```
In drivers/block/loop.c (ffffffff81708ef7)
Location: include/linux/fs.h:3319
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
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
In mm/page_io.c (ffffffff81285fe9)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812da3fd)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff81316825)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8133b40e)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813406f3)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
```
In drivers/block/loop.c (ffffffff8172d1d5)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
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
In mm/page_io.c (ffff8000103205a0)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffff80001037f754)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffff8000103cd19c)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffff8000103fa0d4)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffff800010400684)
Location: include/linux/fs.h:3381
Inline: True
```
```
In drivers/block/loop.c (ffff800010924b14)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
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
In mm/page_io.c (c0539030)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c0569da4)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/splice.c (c05a8d40)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c05ce2a0)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c05d20a8)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
```
In drivers/block/loop.c (c0a082bc)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
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
In mm/page_io.c (c0000000003f573c)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c000000000475850)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (c0000000004cef28)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c000000000503734)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c000000000509ef8)
Location: include/linux/fs.h:3381
Inline: True
```
```
In drivers/block/loop.c (c0000000009c8c04)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
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
In mm/page_io.c (ffffffe000221cc4)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffe00025542c)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffe00028a5ba)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffe0002a9a82)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffe0002acdbc)
Location: include/linux/fs.h:3381
Inline: True
```
```
In drivers/block/loop.c (ffffffe0005a1c20)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
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
In mm/page_io.c (ffffffff8127e639)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d29dd)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130ee05)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813339ee)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81338cd3)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
```
In drivers/block/loop.c (ffffffff816f2fb5)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
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
In mm/page_io.c (ffffffff81270469)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c365d)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff812ffa15)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8132465e)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81329a03)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
```
In drivers/block/loop.c (ffffffff816cd0b5)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
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
In mm/page_io.c (ffffffff8127c3d9)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d07ed)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130cbf5)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813314be)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813367a3)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
```
In drivers/block/loop.c (ffffffff81720695)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
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
In mm/page_io.c (ffffffff8128bfa9)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812e161d)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8131e405)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813440ae)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81349873)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
```
In drivers/block/loop.c (ffffffff8173ba55)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
</details>
</li>
</ul>

## Differences
