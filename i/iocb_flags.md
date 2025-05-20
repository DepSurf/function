# Function: <code>iocb_flags</code>

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
In mm/page_io.c (ffffffff811d22d1)
Location: include/linux/fs.h:2882
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8120be5d)
Location: include/linux/fs.h:2882
Inline: True
```
```
In fs/aio.c (ffffffff8125d605)
Location: include/linux/fs.h:2882
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
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
In mm/page_io.c (ffffffff811efea5)
Location: include/linux/fs.h:3027
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81231949)
Location: include/linux/fs.h:3027
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff812862e8)
Location: include/linux/fs.h:3027
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
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
In mm/page_io.c (ffffffff812007e1)
Location: include/linux/fs.h:2997
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81243ef9)
Location: include/linux/fs.h:2997
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff81279027)
Location: include/linux/fs.h:2997
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8129970b)
Location: include/linux/fs.h:2997
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
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
In mm/page_io.c (ffffffff8120b41b)
Location: include/linux/fs.h:3148
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8124f891)
Location: include/linux/fs.h:3148
Inline: True
```
```
In fs/splice.c (ffffffff81286587)
Location: include/linux/fs.h:3148
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812a73ef)
Location: include/linux/fs.h:3148
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
In mm/page_io.c (ffffffff812248db)
Location: include/linux/fs.h:3228
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812717d1)
Location: include/linux/fs.h:3228
Inline: True
```
```
In fs/splice.c (ffffffff812a9087)
Location: include/linux/fs.h:3228
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812ca784)
Location: include/linux/fs.h:3228
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:3228
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
In mm/page_io.c (ffffffff81246f65)
Location: include/linux/fs.h:3253
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81297634)
Location: include/linux/fs.h:3253
Inline: True
```
```
In fs/splice.c (ffffffff812cfbc0)
Location: include/linux/fs.h:3253
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812f2695)
Location: include/linux/fs.h:3253
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/fuse/file.c (ffffffff813cae97)
Location: include/linux/fs.h:3253
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
In mm/page_io.c (ffffffff8125b39c)
Location: include/linux/fs.h:3332
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812ac2e4)
Location: include/linux/fs.h:3332
Inline: True
```
```
In fs/splice.c (ffffffff812e4fad)
Location: include/linux/fs.h:3332
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81307081)
Location: include/linux/fs.h:3332
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:3332
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
In mm/page_io.c (ffffffff812764eb)
Location: include/linux/fs.h:3343
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c89e3)
Location: include/linux/fs.h:3343
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130379d)
Location: include/linux/fs.h:3343
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81328651)
Location: include/linux/fs.h:3343
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8132d62e)
Location: include/linux/fs.h:3343
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:3343
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
In mm/page_io.c (ffffffff81285fdb)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812da3f3)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8131681d)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8133b401)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813406e6)
Location: include/linux/fs.h:3405
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
In mm/page_io.c (ffffffff812b8305)
Location: include/linux/fs.h:3455
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81310853)
Location: include/linux/fs.h:3455
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (ffffffff8135048b)
Location: include/linux/fs.h:3455
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81374fdf)
Location: include/linux/fs.h:3455
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8137b2db)
Location: include/linux/fs.h:3455
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
In mm/page_io.c (ffffffff812c39cf)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8131d263)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff8134df57)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff8135d32b)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81382eb1)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81389f52)
Location: include/linux/fs.h:3248
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
In mm/page_io.c (ffffffff812ca79a)
Location: include/linux/fs.h:3500
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff813233d3)
Location: include/linux/fs.h:3500
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff81355287)
Location: include/linux/fs.h:3500
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff81363d8b)
Location: include/linux/fs.h:3500
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81389f21)
Location: include/linux/fs.h:3500
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8139109b)
Location: include/linux/fs.h:3500
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
In mm/page_io.c (ffffffff8130f797)
Location: include/linux/fs.h:3480
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff813708c3)
Location: include/linux/fs.h:3480
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff813a3697)
Location: include/linux/fs.h:3480
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff813b25bb)
Location: include/linux/fs.h:3480
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813d7201)
Location: include/linux/fs.h:3480
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813e2e4a)
Location: include/linux/fs.h:3480
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
In mm/page_io.c (ffffffff8137a124)
Location: include/linux/fs.h:3258
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff813ef469)
Location: include/linux/fs.h:3258
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff81427459)
Location: include/linux/fs.h:3258
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff814375f8)
Location: include/linux/fs.h:3258
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81460e11)
Location: include/linux/fs.h:3258
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In io_uring/io_uring.c (ffffffff816c74c6)
Location: include/linux/fs.h:3258
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rw_init_file
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
In fs/open.c (ffffffff81473ec4)
Location: include/linux/fs.h:3400
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff8147ca36)
Location: include/linux/fs.h:3400
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/fcntl.c (ffffffff814948c7)
Location: include/linux/fs.h:3400
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
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
In fs/open.c (ffffffff814a86df)
Location: include/linux/fs.h:3015
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814b16d2)
Location: include/linux/fs.h:3015
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/fcntl.c (ffffffff814c9930)
Location: include/linux/fs.h:3015
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
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
In fs/open.c (ffffffff814d97bf)
Location: include/linux/fs.h:3312
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814e2ea2)
Location: include/linux/fs.h:3312
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/fcntl.c (ffffffff814fc1e1)
Location: include/linux/fs.h:3312
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
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
In mm/page_io.c (ffff800010320594)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffff80001037f74c)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffff8000103cd19c)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffff8000103fa0c8)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffff800010400678)
Location: include/linux/fs.h:3405
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
In mm/page_io.c (c0539024)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c0569da4)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/splice.c (c05a8d38)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c05ce294)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c05d209c)
Location: include/linux/fs.h:3405
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
In mm/page_io.c (c0000000003f5730)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c000000000475844)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (c0000000004cef20)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c000000000503728)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c000000000509eec)
Location: include/linux/fs.h:3405
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
In mm/page_io.c (ffffffe000221cb8)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffe000255420)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffe00028a5ac)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffe0002a9a78)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffe0002acdb2)
Location: include/linux/fs.h:3405
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
In mm/page_io.c (ffffffff8127e62b)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d29d3)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130edfd)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813339e1)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81338cc6)
Location: include/linux/fs.h:3405
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
In mm/page_io.c (ffffffff8127045b)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c3653)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff812ffa0d)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81324651)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813299f6)
Location: include/linux/fs.h:3405
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
In mm/page_io.c (ffffffff8127c3cb)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d07e3)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130cbed)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813314b1)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81336796)
Location: include/linux/fs.h:3405
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
In mm/page_io.c (ffffffff8128bf9b)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812e1613)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8131e3fd)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813440a1)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81349866)
Location: include/linux/fs.h:3405
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
</ul>

## Differences
