# Function: <code>get_current_ioprio</code>

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
In mm/page_io.c (ffffffff8125b417)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812ac360)
Location: include/linux/ioprio.h:77
Inline: True
```
```
In fs/splice.c (ffffffff812e5016)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81307113)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/fuse/file.c (ffffffff813e291a)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/page_io.c (ffffffff81276560)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c8a56)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff81303806)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813286e3)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8132d6b9)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
```
In fs/fuse/file.c (ffffffff8140e5e1)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/page_io.c (ffffffff81286050)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812da466)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff81316886)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8133b493)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81340759)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In mm/page_io.c (ffffffff812b834c)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff813108b1)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (ffffffff813504e2)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8137505d)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8137b37c)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In mm/page_io.c (ffffffff812c3a19)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8131d2c4)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff8134dfb8)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff8135d385)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81382f2d)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81389fec)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In mm/page_io.c (ffffffff812ca7e3)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81323434)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff813552e8)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff81363de5)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81389f9d)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81391144)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In mm/page_io.c (ffffffff8130f7e0)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81370924)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff813a36f8)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff813b2615)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813d727d)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813e2ef7)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In mm/page_io.c (ffffffff8137a16a)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff813ef4ad)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff8142748a)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff8143763c)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81460e7b)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In io_uring/io_uring.c (ffffffff816cacb0)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_prep_rw
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
In mm/page_io.c (ffffffff813f7c23)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/read_write.c (ffffffff814775e8)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/seq_file.c (ffffffff814b3f4e)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff814c5713)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff814f0e6c)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In block/blk-mq.c (ffffffff81748013)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In io_uring/rw.c (ffffffff817a3f71)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
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
In mm/filemap.c (ffffffff8139250e)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
```
```
In mm/page_io.c (ffffffff8142ade3)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/read_write.c (ffffffff814abf68)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/seq_file.c (ffffffff814e8fde)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff814fa835)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - fs/splice.c:copy_splice_read
```
```
In fs/aio.c (ffffffff81527c7c)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In block/blk-mq.c (ffffffff817846d6)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In io_uring/rw.c (ffffffff817e4fd1)
Location: include/linux/ioprio.h:58
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
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
In mm/filemap.c (ffffffff813bc151)
Location: include/linux/ioprio.h:81
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
```
```
In mm/page_io.c (ffffffff8146458b)
Location: include/linux/ioprio.h:81
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/read_write.c (ffffffff814dd318)
Location: include/linux/ioprio.h:81
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/seq_file.c (ffffffff8151ce65)
Location: include/linux/ioprio.h:81
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff815307f9)
Location: include/linux/ioprio.h:81
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:copy_splice_read
```
```
In fs/aio.c (ffffffff8155c9a8)
Location: include/linux/ioprio.h:81
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In block/blk-core.c (ffffffff817b46bc)
Location: include/linux/ioprio.h:81
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In io_uring/rw.c (ffffffff81829453)
Location: include/linux/ioprio.h:81
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
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
In mm/page_io.c (ffff8000103205e8)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffff80001037f7a0)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffff8000103cd1f0)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffff8000103fa144)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffff8000104006d8)
Location: include/linux/ioprio.h:77
Inline: True
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
In mm/page_io.c (c0539064)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c0569dfc)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/splice.c (c05a8d8c)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c05ce310)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c05d20f4)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In mm/page_io.c (c0000000003f57b4)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c0000000004758b4)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (c0000000004cef8c)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c0000000005037c0)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c000000000509f64)
Location: include/linux/ioprio.h:77
Inline: True
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
In mm/page_io.c (ffffffe000221d0a)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffe00025547c)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffe00028a600)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffe0002a9ae4)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffe0002ace0e)
Location: include/linux/ioprio.h:77
Inline: True
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
In mm/page_io.c (ffffffff8127e6a0)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d2a46)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130ee66)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81333a73)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81338d39)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In mm/page_io.c (ffffffff812704d0)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c36c6)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff812ffa76)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813246e3)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81329a69)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In mm/page_io.c (ffffffff8127c440)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d0856)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130cc56)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81331543)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81336809)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In mm/page_io.c (ffffffff8128c010)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812e1686)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8131e466)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81344133)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813498d9)
Location: include/linux/ioprio.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
</ul>

## Differences
