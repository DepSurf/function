# Function: <code>iov_iter_is_bvec</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:67
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
In block/bio.c (ffffffff814c6d45)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:69
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
In fs/io_uring.c (ffffffff81340ae8)
Location: include/linux/uio.h:69
Inline: True
```
```
In block/bio.c (ffffffff814dfbb5)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:69
Inline: True
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
In fs/io_uring.c (ffffffff8137c052)
Location: include/linux/uio.h:69
Inline: True
```
```
In block/bio.c (ffffffff8153f845)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:69
Inline: True
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
In fs/io_uring.c (ffffffff81389057)
Location: include/linux/uio.h:68
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_map_rw
  - fs/io_uring.c:loop_rw_iter
```
```
In block/bio.c (ffffffff8155c065)
Location: include/linux/uio.h:68
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:68
Inline: True
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
In fs/block_dev.c (ffffffff81373ca4)
Location: include/linux/uio.h:71
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/io_uring.c (ffffffff81390167)
Location: include/linux/uio.h:71
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_map_rw
  - fs/io_uring.c:loop_rw_iter
  - fs/io_uring.c:loop_rw_iter
```
```
In fs/iomap/direct-io.c (ffffffff813c5e34)
Location: include/linux/uio.h:71
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In block/bio.c (ffffffff815645af)
Location: include/linux/uio.h:71
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:71
Inline: True
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
In fs/io_uring.c (ffffffff813ddc49)
Location: include/linux/uio.h:81
Inline: True
Inline callers:
  - fs/io_uring.c:loop_rw_iter
  - fs/io_uring.c:loop_rw_iter
```
```
In fs/iomap/direct-io.c (ffffffff814157f5)
Location: include/linux/uio.h:81
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/fops.c (ffffffff815c5ed2)
Location: include/linux/uio.h:81
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff815c8c75)
Location: include/linux/uio.h:81
Inline: True
```
```
In lib/iov_iter.c (ffffffff81619d90)
Location: include/linux/uio.h:81
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_restore
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
In fs/iomap/direct-io.c (ffffffff8148cf23)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/fops.c (ffffffff816705fa)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff81673a48)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In io_uring/io_uring.c (ffffffff816c6f8a)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_map_rw
  - io_uring/io_uring.c:loop_rw_iter
  - io_uring/io_uring.c:loop_rw_iter
```
```
In lib/iov_iter.c (ffffffff816e7250)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_restore
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
In fs/iomap/direct-io.c (ffffffff81520433)
Location: include/linux/uio.h:97
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/fops.c (ffffffff8172bc15)
Location: include/linux/uio.h:97
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff8172f9d5)
Location: include/linux/uio.h:97
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff8173c426)
Location: include/linux/uio.h:97
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In io_uring/rw.c (ffffffff817a35ea)
Location: include/linux/uio.h:97
Inline: True
Inline callers:
  - io_uring/rw.c:io_req_map_rw
  - io_uring/rw.c:loop_rw_iter
  - io_uring/rw.c:loop_rw_iter
```
```
In lib/iov_iter.c (ffffffff817d6a70)
Location: include/linux/uio.h:97
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_restore
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
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
In fs/iomap/direct-io.c (ffffffff815583f1)
Location: include/linux/uio.h:124
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/fops.c (ffffffff81767cfd)
Location: include/linux/uio.h:124
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
```
```
In block/bio.c (ffffffff8176bc0a)
Location: include/linux/uio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff817789c6)
Location: include/linux/uio.h:124
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In io_uring/rw.c (ffffffff817e458a)
Location: include/linux/uio.h:124
Inline: True
Inline callers:
  - io_uring/rw.c:io_req_map_rw
  - io_uring/rw.c:loop_rw_iter
```
```
In lib/iov_iter.c (ffffffff81815a90)
Location: include/linux/uio.h:124
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_restore
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
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
In fs/iomap/direct-io.c (ffffffff8158eaf0)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/fops.c (ffffffff817a995a)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
```
```
In block/bio.c (ffffffff817ae0a6)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff817bad96)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In io_uring/rw.c (ffffffff8182865a)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - io_uring/rw.c:io_req_map_rw
  - io_uring/rw.c:loop_rw_iter
```
```
In lib/iov_iter.c (ffffffff8185abd0)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_restore
  - lib/iov_iter.c:dup_iter
```
```
In net/core/skbuff.c (0)
Location: include/linux/uio.h:119
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/uio.h:119
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
In fs/io_uring.c (ffff800010400abc)
Location: include/linux/uio.h:69
Inline: True
```
```
In block/bio.c (ffff8000105dc75c)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:69
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
In fs/io_uring.c (c05d29d4)
Location: include/linux/uio.h:69
Inline: True
```
```
In block/bio.c (c0789b78)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:69
Inline: True
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
In fs/io_uring.c (c00000000050a4a0)
Location: include/linux/uio.h:69
Inline: True
```
```
In block/bio.c (c00000000076d864)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:69
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
In fs/io_uring.c (ffffffe0002ad0e4)
Location: include/linux/uio.h:69
Inline: True
```
```
In block/bio.c (ffffffe00041fb12)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:69
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
In fs/io_uring.c (ffffffff813390c8)
Location: include/linux/uio.h:69
Inline: True
```
```
In block/bio.c (ffffffff814d8195)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:69
Inline: True
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
In fs/io_uring.c (ffffffff81329df8)
Location: include/linux/uio.h:69
Inline: True
```
```
In block/bio.c (ffffffff814c8b45)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:69
Inline: True
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
In fs/io_uring.c (ffffffff81336b98)
Location: include/linux/uio.h:69
Inline: True
```
```
In block/bio.c (ffffffff814d4225)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:69
Inline: True
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
In fs/io_uring.c (ffffffff81349c68)
Location: include/linux/uio.h:69
Inline: True
```
```
In block/bio.c (ffffffff814ecdd5)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:69
Inline: True
```
</details>
</li>
</ul>

## Differences
