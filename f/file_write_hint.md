# Function: <code>file_write_hint</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8120b462)
Location: include/linux/fs.h:1892
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8124f904)
Location: include/linux/fs.h:1892
Inline: True
```
```
In fs/fcntl.c (ffffffff81265d17)
Location: include/linux/fs.h:1892
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffffffff812865e0)
Location: include/linux/fs.h:1892
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812a7450)
Location: include/linux/fs.h:1892
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
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
In mm/page_io.c (ffffffff81224922)
Location: include/linux/fs.h:1922
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81271844)
Location: include/linux/fs.h:1922
Inline: True
```
```
In fs/fcntl.c (ffffffff812885f7)
Location: include/linux/fs.h:1922
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffffffff812a90e0)
Location: include/linux/fs.h:1922
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812ca7e5)
Location: include/linux/fs.h:1922
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:1922
Inline: True
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
In mm/page_io.c (ffffffff81246fcc)
Location: include/linux/fs.h:1942
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8129769b)
Location: include/linux/fs.h:1942
Inline: True
```
```
In fs/fcntl.c (ffffffff812aeb1b)
Location: include/linux/fs.h:1942
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffffffff812cfc16)
Location: include/linux/fs.h:1942
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812f2704)
Location: include/linux/fs.h:1942
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/fuse/file.c (ffffffff813caef4)
Location: include/linux/fs.h:1942
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
In mm/page_io.c (ffffffff8125b403)
Location: include/linux/fs.h:2024
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812ac34b)
Location: include/linux/fs.h:2024
Inline: True
```
```
In fs/fcntl.c (ffffffff812c3c0c)
Location: include/linux/fs.h:2024
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffffffff812e5003)
Location: include/linux/fs.h:2024
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813070ed)
Location: include/linux/fs.h:2024
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:2024
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
In mm/page_io.c (ffffffff8127654d)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c8a3d)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/fcntl.c (ffffffff812e05f1)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffffffff813037f3)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813286bd)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8132d68f)
Location: include/linux/fs.h:2031
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:2031
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
In mm/page_io.c (ffffffff8128603d)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812da44d)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/fcntl.c (ffffffff812f2097)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffffffff81316873)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8133b46d)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81340730)
Location: include/linux/fs.h:2066
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
In mm/page_io.c (ffffffff812b8339)
Location: include/linux/fs.h:2080
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8131089e)
Location: include/linux/fs.h:2080
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
```
```
In fs/fcntl.c (ffffffff8132a2c8)
Location: include/linux/fs.h:2080
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffffffff813504cf)
Location: include/linux/fs.h:2080
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81375037)
Location: include/linux/fs.h:2080
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8137b2c1)
Location: include/linux/fs.h:2080
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
In mm/page_io.c (ffffffff812c3a06)
Location: include/linux/fs.h:2050
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8131d2b1)
Location: include/linux/fs.h:2050
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/fcntl.c (ffffffff81335838)
Location: include/linux/fs.h:2050
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/seq_file.c (ffffffff8134dfa5)
Location: include/linux/fs.h:2050
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff8135d372)
Location: include/linux/fs.h:2050
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81382f0f)
Location: include/linux/fs.h:2050
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81389f38)
Location: include/linux/fs.h:2050
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
In mm/page_io.c (ffffffff812ca7d0)
Location: include/linux/fs.h:2258
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81323421)
Location: include/linux/fs.h:2258
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/fcntl.c (ffffffff8133b97e)
Location: include/linux/fs.h:2258
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/seq_file.c (ffffffff813552d5)
Location: include/linux/fs.h:2258
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff81363dd2)
Location: include/linux/fs.h:2258
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81389f7f)
Location: include/linux/fs.h:2258
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81391081)
Location: include/linux/fs.h:2258
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
In mm/page_io.c (ffffffff8130f7cd)
Location: include/linux/fs.h:2312
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81370911)
Location: include/linux/fs.h:2312
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/fcntl.c (ffffffff813895f5)
Location: include/linux/fs.h:2312
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/seq_file.c (ffffffff813a36e5)
Location: include/linux/fs.h:2312
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff813b2602)
Location: include/linux/fs.h:2312
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813d725f)
Location: include/linux/fs.h:2312
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813e2e30)
Location: include/linux/fs.h:2312
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
In mm/page_io.c (ffff8000103205d8)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffff80001037f794)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/fcntl.c (ffff80001039bf74)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffff8000103cd1e4)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffff8000103fa128)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffff8000104006b8)
Location: include/linux/fs.h:2066
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
In mm/page_io.c (c0539054)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c0569dec)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/fcntl.c (c0582178)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (c05a8d7c)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c05ce2ec)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c05d20cc)
Location: include/linux/fs.h:2066
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
In mm/page_io.c (c0000000003f57a0)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c0000000004758a0)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
```
```
In fs/fcntl.c (c0000000004971d0)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (c0000000004cef78)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c00000000050379c)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c000000000509f40)
Location: include/linux/fs.h:2066
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
In mm/page_io.c (ffffffe000221cfc)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffe00025546e)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/fcntl.c (ffffffe000268eb4)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/splice.c (ffffffe00028a5f6)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffe0002a9ace)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffe0002acdf2)
Location: include/linux/fs.h:2066
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
In mm/page_io.c (ffffffff8127e68d)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d2a2d)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/fcntl.c (ffffffff812ea677)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffffffff8130ee53)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81333a4d)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81338d10)
Location: include/linux/fs.h:2066
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
In mm/page_io.c (ffffffff812704bd)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c36ad)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/fcntl.c (ffffffff812db2b7)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffffffff812ffa63)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813246bd)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81329a40)
Location: include/linux/fs.h:2066
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
In mm/page_io.c (ffffffff8127c42d)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d083d)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/fcntl.c (ffffffff812e8487)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffffffff8130cc43)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8133151d)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813367e0)
Location: include/linux/fs.h:2066
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
In mm/page_io.c (ffffffff8128bffd)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812e166d)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/fcntl.c (ffffffff812f9439)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/splice.c (ffffffff8131e453)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8134410d)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813498b0)
Location: include/linux/fs.h:2066
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
</ul>

## Differences
