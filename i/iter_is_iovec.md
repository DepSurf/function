# Function: <code>iter_is_iovec</code>

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
In mm/filemap.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/uio.h:109
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/uio.h:110
Inline: True
```
```
In mm/shmem.c (ffffffff811c322a)
Location: include/linux/uio.h:110
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/dax.c (0)
Location: include/linux/uio.h:110
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/uio.h:110
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/uio.h:110
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/uio.h:110
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/uio.h:119
Inline: True
```
```
In mm/shmem.c (ffffffff811d32aa)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (0)
Location: include/linux/uio.h:119
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/uio.h:119
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/uio.h:119
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/uio.h:119
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/uio.h:119
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/uio.h:119
Inline: True
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
In mm/shmem.c (ffffffff811dbb50)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (0)
Location: include/linux/uio.h:192
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/uio.h:192
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/uio.h:192
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/uio.h:192
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:192
Inline: True
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
In mm/shmem.c (ffffffff811f1960)
Location: include/linux/uio.h:190
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (0)
Location: include/linux/uio.h:190
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/uio.h:190
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/uio.h:190
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/uio.h:190
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:190
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
In mm/shmem.c (ffffffff81211e82)
Location: include/linux/uio.h:205
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff812dc251)
Location: include/linux/uio.h:205
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/fuse/dev.c (ffffffff813c3461)
Location: include/linux/uio.h:205
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff813ca868)
Location: include/linux/uio.h:205
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff81489852)
Location: include/linux/uio.h:205
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:205
Inline: True
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
In mm/shmem.c (ffffffff81226032)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff812f1cc9)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812f43f3)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff8132684a)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff813dcd11)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff813e3f87)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff814a3692)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:57
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
In mm/shmem.c (ffffffff812359e5)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8131267b)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81316ad2)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8134d20c)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff81408813)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff8140fd61)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff814d1821)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:59
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
In mm/shmem.c (ffffffff81243c25)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff813255ca)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81329950)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813654be)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff81422a93)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff8142962c)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff814eac41)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:59
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
In mm/shmem.c (ffffffff8126f3b5)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8135fdb2)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81363752)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813ad526)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff81471c7e)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff8147959c)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff8154aab0)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:59
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
In mm/shmem.c (ffffffff8127a725)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8136d62b)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff813709ba)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813beacb)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff8148c4ee)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff814942bf)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff815668f2)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:58
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
In mm/shmem.c (ffffffff8127f867)
Location: include/linux/uio.h:61
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff81373f4e)
Location: include/linux/uio.h:61
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81377256)
Location: include/linux/uio.h:61
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813c5757)
Location: include/linux/uio.h:61
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff81491dee)
Location: include/linux/uio.h:61
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff81499170)
Location: include/linux/uio.h:61
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff8156ee39)
Location: include/linux/uio.h:61
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff815ab3a6)
Location: include/linux/uio.h:61
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_fault_in_readable
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
In mm/shmem.c (ffffffff812bdba0)
Location: include/linux/uio.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/direct-io.c (ffffffff813c382a)
Location: include/linux/uio.h:71
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81415b5f)
Location: include/linux/uio.h:71
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff814e98df)
Location: include/linux/uio.h:71
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff814f0c00)
Location: include/linux/uio.h:71
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/fops.c (ffffffff815c6132)
Location: include/linux/uio.h:71
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-map.c (ffffffff815d3479)
Location: include/linux/uio.h:71
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff816143da)
Location: include/linux/uio.h:71
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
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
In mm/shmem.c (ffffffff8131b55a)
Location: include/linux/uio.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/direct-io.c (ffffffff8144a610)
Location: include/linux/uio.h:73
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8148d341)
Location: include/linux/uio.h:73
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff815780d0)
Location: include/linux/uio.h:73
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff81580827)
Location: include/linux/uio.h:73
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/fops.c (ffffffff8167066e)
Location: include/linux/uio.h:73
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-map.c (ffffffff8167f226)
Location: include/linux/uio.h:73
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff816e0e0a)
Location: include/linux/uio.h:73
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
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
In block/blk-map.c (0)
Location: include/linux/uio.h:87
Inline: True
```
```
In lib/iov_iter.c (ffffffff817d17fb)
Location: include/linux/uio.h:87
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
In block/blk-map.c (ffffffff81777b72)
Location: include/linux/uio.h:114
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In io_uring/net.c (ffffffff817d6685)
Location: include/linux/uio.h:114
Inline: True
Inline callers:
  - io_uring/net.c:io_setup_async_msg
```
```
In lib/iov_iter.c (ffffffff8181060b)
Location: include/linux/uio.h:114
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
In mm/shmem.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In block/blk-map.c (ffffffff817b9d96)
Location: include/linux/uio.h:109
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In io_uring/net.c (ffffffff8181a54a)
Location: include/linux/uio.h:109
Inline: True
Inline callers:
  - io_uring/net.c:io_setup_async_msg
```
```
In lib/iov_iter.c (ffffffff8185605b)
Location: include/linux/uio.h:109
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/uio.h:109
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/uio.h:109
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
In mm/shmem.c (ffff8000102d5ed0)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffff8000103e0dc4)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffff8000103e4d80)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffff80001042d1b0)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffff800010505814)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffff80001050d60c)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffff8000105e9790)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:59
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
In mm/shmem.c (c04fe16c)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (c05b7ff4)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (c05bcce8)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (c05f6210)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (c06c1bf8)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (c06c8e58)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (c0795a80)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:59
Inline: True
```
```
In sound/core/pcm_native.c (c0c9489c)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_writev
  - sound/core/pcm_native.c:snd_pcm_readv
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
In mm/shmem.c (c000000000395fc8)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (c0000000004e6e18)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (c0000000004eb0e4)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (c00000000053d7b4)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (c00000000064ae2c)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (c000000000654264)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (c00000000077e244)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:59
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
In mm/shmem.c (ffffffe0001f183e)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffe000297776)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffe00029a8f2)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffe0002c9834)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffe000372164)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffe00037844c)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffe000429c3a)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:59
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
In mm/shmem.c (ffffffff8123c275)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8131dbaa)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81321f30)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8135da9e)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff8141b073)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff81421c0c)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff814e3221)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:59
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
In mm/shmem.c (ffffffff8122f275)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8130e74a)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81312ad0)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8134e73e)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff8140baf3)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff8141268c)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff814d3ba1)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:59
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
In mm/shmem.c (ffffffff8123a015)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8131b67a)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8131fa00)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8135b56e)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff81417213)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff8141ddac)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff814df2b1)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:59
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
In mm/shmem.c (ffffffff81249705)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8132d45a)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81331720)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8136ecbe)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff8142dfa3)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff81434b0c)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff814f8121)
Location: include/linux/uio.h:59
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:59
Inline: True
```
</details>
</li>
</ul>

## Differences
