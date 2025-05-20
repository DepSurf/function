# Function: <code>ki_hint_validate</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81246fdb)
Location: include/linux/fs.h:1952
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812976ab)
Location: include/linux/fs.h:1952
Inline: True
```
```
In fs/splice.c (ffffffff812cfc24)
Location: include/linux/fs.h:1952
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812f2715)
Location: include/linux/fs.h:1952
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/fuse/file.c (ffffffff813caf02)
Location: include/linux/fs.h:1952
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/page_io.c (ffffffff8125b417)
Location: include/linux/fs.h:2034
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812ac360)
Location: include/linux/fs.h:2034
Inline: True
```
```
In fs/splice.c (ffffffff812e5016)
Location: include/linux/fs.h:2034
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81307103)
Location: include/linux/fs.h:2034
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:2034
Inline: True
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
In mm/page_io.c (ffffffff81276555)
Location: include/linux/fs.h:2041
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c8a4a)
Location: include/linux/fs.h:2041
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff813037fb)
Location: include/linux/fs.h:2041
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813286c8)
Location: include/linux/fs.h:2041
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8132d69a)
Location: include/linux/fs.h:2041
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:2041
Inline: True
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
In mm/page_io.c (ffffffff81286045)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812da45a)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8131687b)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8133b478)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8134073b)
Location: include/linux/fs.h:2076
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
In mm/page_io.c (ffffffff812b8341)
Location: include/linux/fs.h:2090
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff813108a6)
Location: include/linux/fs.h:2090
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (ffffffff813504d7)
Location: include/linux/fs.h:2090
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81375042)
Location: include/linux/fs.h:2090
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8137b2cc)
Location: include/linux/fs.h:2090
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
In mm/page_io.c (ffffffff812c3a0e)
Location: include/linux/fs.h:2060
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8131d2b9)
Location: include/linux/fs.h:2060
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff8134dfad)
Location: include/linux/fs.h:2060
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff8135d37a)
Location: include/linux/fs.h:2060
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81382f16)
Location: include/linux/fs.h:2060
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81389f43)
Location: include/linux/fs.h:2060
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
In mm/page_io.c (ffffffff812ca7d8)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81323429)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff813552dd)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff81363dda)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81389f86)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8139108c)
Location: include/linux/fs.h:2268
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
In mm/page_io.c (ffffffff8130f7d5)
Location: include/linux/fs.h:2322
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81370919)
Location: include/linux/fs.h:2322
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff813a36ed)
Location: include/linux/fs.h:2322
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff813b260a)
Location: include/linux/fs.h:2322
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813d7266)
Location: include/linux/fs.h:2322
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813e2e3b)
Location: include/linux/fs.h:2322
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
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
In mm/page_io.c (ffff8000103205e0)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffff80001037f798)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffff8000103cd1e8)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffff8000103fa130)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffff8000104006c0)
Location: include/linux/fs.h:2076
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
In mm/page_io.c (c053905c)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c0569df4)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/splice.c (c05a8d84)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c05ce2f8)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c05d20d8)
Location: include/linux/fs.h:2076
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
In mm/page_io.c (c0000000003f57ac)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c0000000004758ac)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (c0000000004cef84)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c0000000005037a8)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c000000000509f4c)
Location: include/linux/fs.h:2076
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
In mm/page_io.c (ffffffe000221d02)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffe000255474)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffe00028a5fa)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffe0002a9ad2)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffe0002acdf6)
Location: include/linux/fs.h:2076
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
In mm/page_io.c (ffffffff8127e695)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d2a3a)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130ee5b)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81333a58)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81338d1b)
Location: include/linux/fs.h:2076
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
In mm/page_io.c (ffffffff812704c5)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c36ba)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff812ffa6b)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813246c8)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81329a4b)
Location: include/linux/fs.h:2076
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
In mm/page_io.c (ffffffff8127c435)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d084a)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130cc4b)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81331528)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813367eb)
Location: include/linux/fs.h:2076
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
In mm/page_io.c (ffffffff8128c005)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812e167a)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8131e45b)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81344118)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813498bb)
Location: include/linux/fs.h:2076
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
</ul>

## Differences
