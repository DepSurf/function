# Function: <code>iov_iter_type</code>

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
In mm/filemap.c (ffffffff811fff36)
Location: include/linux/uio.h:52
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81226032)
Location: include/linux/uio.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff812f1cc9)
Location: include/linux/uio.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (0)
Location: include/linux/uio.h:52
Inline: True
```
```
In fs/iomap.c (ffffffff8132684a)
Location: include/linux/uio.h:52
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff813dcd11)
Location: include/linux/uio.h:52
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff813e3fcd)
Location: include/linux/uio.h:52
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff814a3692)
Location: include/linux/uio.h:52
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff814da273)
Location: include/linux/uio.h:52
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff81216f89)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff812359e5)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8131267b)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81316ad2)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8134d20c)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff81408813)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff8140fdb5)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (ffffffff814c6d45)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff814d1821)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff81505a93)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff81224899)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81243c25)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff813255ca)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81329950)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff81340ae8)
Location: include/linux/uio.h:54
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff813654be)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff81422a93)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff8142968c)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (ffffffff814dfbb5)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff814eac41)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff81523a43)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff812522b9)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8126f3b5)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8135fdb2)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81363752)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff8137c052)
Location: include/linux/uio.h:54
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff813ad526)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff81471c7e)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff814795ed)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (ffffffff8153f845)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff8154aab0)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff81586de3)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_single_seg_count
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff8125b92e)
Location: include/linux/uio.h:53
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
```
```
In mm/shmem.c (ffffffff8127a725)
Location: include/linux/uio.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8136d62b)
Location: include/linux/uio.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff813709ba)
Location: include/linux/uio.h:53
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff81389057)
Location: include/linux/uio.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_map_rw
  - fs/io_uring.c:loop_rw_iter
```
```
In fs/iomap/direct-io.c (ffffffff813beacb)
Location: include/linux/uio.h:53
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff8148c4ee)
Location: include/linux/uio.h:53
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff81494310)
Location: include/linux/uio.h:53
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (ffffffff8155c065)
Location: include/linux/uio.h:53
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff815668f2)
Location: include/linux/uio.h:53
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff815a40b3)
Location: include/linux/uio.h:53
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_single_seg_count
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff81261de1)
Location: include/linux/uio.h:56
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
```
```
In mm/shmem.c (ffffffff8127f867)
Location: include/linux/uio.h:56
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff81373ca4)
Location: include/linux/uio.h:56
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81377256)
Location: include/linux/uio.h:56
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff81390167)
Location: include/linux/uio.h:56
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_map_rw
  - fs/io_uring.c:loop_rw_iter
  - fs/io_uring.c:loop_rw_iter
```
```
In fs/iomap/direct-io.c (ffffffff813c5757)
Location: include/linux/uio.h:56
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/fuse/dev.c (ffffffff81491dee)
Location: include/linux/uio.h:56
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff814991d0)
Location: include/linux/uio.h:56
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (ffffffff815645af)
Location: include/linux/uio.h:56
Inline: True
```
```
In block/blk-map.c (ffffffff8156ee39)
Location: include/linux/uio.h:56
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff815aafa3)
Location: include/linux/uio.h:56
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_single_seg_count
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff8129e42a)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
```
```
In mm/shmem.c (ffffffff812bdba0)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/direct-io.c (ffffffff813c382a)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff813ddc49)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - fs/io_uring.c:loop_rw_iter
  - fs/io_uring.c:loop_rw_iter
```
```
In fs/iomap/direct-io.c (ffffffff81415b5f)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/fuse/dev.c (ffffffff814e98df)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff814f0c5e)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/fops.c (ffffffff815c5ed2)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff815c8c75)
Location: include/linux/uio.h:58
Inline: True
```
```
In block/blk-map.c (ffffffff815d3479)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff81619d90)
Location: include/linux/uio.h:58
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_restore
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff812f2150)
Location: include/linux/uio.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
```
```
In mm/shmem.c (ffffffff8131b55a)
Location: include/linux/uio.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/direct-io.c (ffffffff8144a610)
Location: include/linux/uio.h:60
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8148d341)
Location: include/linux/uio.h:60
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/fuse/dev.c (ffffffff815780d0)
Location: include/linux/uio.h:60
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff815804f2)
Location: include/linux/uio.h:60
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/fops.c (ffffffff816705fa)
Location: include/linux/uio.h:60
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff81673a48)
Location: include/linux/uio.h:60
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff8167f226)
Location: include/linux/uio.h:60
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In io_uring/io_uring.c (ffffffff816c6f8a)
Location: include/linux/uio.h:60
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_map_rw
  - io_uring/io_uring.c:loop_rw_iter
  - io_uring/io_uring.c:loop_rw_iter
```
```
In lib/iov_iter.c (ffffffff816e7250)
Location: include/linux/uio.h:60
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_restore
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff8135ca30)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
```
```
In fs/iomap/direct-io.c (ffffffff81520433)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/fuse/file.c (ffffffff816262a7)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/fops.c (ffffffff8172bc15)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff8172f9d5)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff8173c426)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In io_uring/rw.c (ffffffff817a35ea)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - io_uring/rw.c:io_req_map_rw
  - io_uring/rw.c:loop_rw_iter
  - io_uring/rw.c:loop_rw_iter
```
```
In lib/iov_iter.c (ffffffff817d6a70)
Location: include/linux/uio.h:69
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_restore
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_is_aligned
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
Location: include/linux/uio.h:96
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/fuse/file.c (ffffffff8165e69e)
Location: include/linux/uio.h:96
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/fops.c (ffffffff81767cfd)
Location: include/linux/uio.h:96
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
```
```
In block/bio.c (ffffffff8176bc0a)
Location: include/linux/uio.h:96
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff817789c6)
Location: include/linux/uio.h:96
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_alloc_map_data
```
```
In io_uring/net.c (ffffffff817d6685)
Location: include/linux/uio.h:96
Inline: True
Inline callers:
  - io_uring/net.c:io_setup_async_msg
```
```
In io_uring/rw.c (ffffffff817e458a)
Location: include/linux/uio.h:96
Inline: True
Inline callers:
  - io_uring/rw.c:io_req_map_rw
  - io_uring/rw.c:loop_rw_iter
  - io_uring/rw.c:loop_rw_iter
```
```
In lib/scatterlist.c (ffffffff8180df46)
Location: include/linux/uio.h:96
Inline: True
```
```
In lib/iov_iter.c (ffffffff81814696)
Location: include/linux/uio.h:96
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_restore
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:first_iovec_segment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_is_aligned
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In mm/shmem.c (ffffffff813eb0be)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/direct-io.c (ffffffff81545f39)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8158efcd)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/fuse/dev.c (ffffffff8168e4c8)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff81698440)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/fops.c (ffffffff817a995a)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff817ae0a6)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff817bad96)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_alloc_map_data
```
```
In io_uring/net.c (ffffffff8181a54a)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - io_uring/net.c:io_setup_async_msg
```
```
In io_uring/rw.c (ffffffff8182865a)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - io_uring/rw.c:io_req_map_rw
  - io_uring/rw.c:loop_rw_iter
  - io_uring/rw.c:loop_rw_iter
```
```
In lib/scatterlist.c (ffffffff81853be6)
Location: include/linux/uio.h:91
Inline: True
```
```
In lib/iov_iter.c (ffffffff818594ca)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_restore
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_is_aligned
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In net/core/skbuff.c (ffffffff81ece22e)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
```
```
In net/core/datagram.c (ffffffff81edd57a)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
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
In mm/filemap.c (ffff8000102b1c48)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffff8000102d5ed0)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffff8000103e0dc4)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffff8000103e4d80)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffff800010400abc)
Location: include/linux/uio.h:54
Inline: True
```
```
In fs/iomap/direct-io.c (ffff80001042d1b0)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffff800010505814)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffff80001050d64c)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (ffff8000105dc75c)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffff8000105e9790)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffff80001062d95c)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (c04debb4)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (c04fe16c)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (c05b7ff4)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (c05bcce8)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (c05d29d4)
Location: include/linux/uio.h:54
Inline: True
```
```
In fs/iomap/direct-io.c (c05f6210)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (c06c1bf8)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (c06c8edc)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (c0789b78)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (c0795a80)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (c07d4574)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In sound/core/pcm_native.c (c0c9489c)
Location: include/linux/uio.h:54
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
In mm/filemap.c (c000000000367c98)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (c000000000395fc8)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (c0000000004e6e18)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (c0000000004eb0e4)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (c00000000050a4a0)
Location: include/linux/uio.h:54
Inline: True
```
```
In fs/iomap/direct-io.c (c00000000053d7b4)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (c00000000064ae2c)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (c0000000006542dc)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (c00000000076d864)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (c00000000077e244)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (c0000000007d0e44)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffe0001d7742)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffe0001f183e)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffe000297776)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffe00029a932)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffe0002ad0e4)
Location: include/linux/uio.h:54
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffe0002c9834)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffe000372164)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffe000378480)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (ffffffe00041fb12)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffe000429c3a)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffe00045e53c)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff8121cee9)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8123c275)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8131dbaa)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81321f30)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff813390c8)
Location: include/linux/uio.h:54
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135da9e)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff8141b073)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff81421c6c)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (ffffffff814d8195)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff814e3221)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff8151c023)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff812100bf)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8122f275)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8130e74a)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81312ad0)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff81329df8)
Location: include/linux/uio.h:54
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134e73e)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff8140baf3)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff814126ec)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (ffffffff814c8b45)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff814d3ba1)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff8150c313)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff8121ac89)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8123a015)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8131b67a)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8131fa00)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff81336b98)
Location: include/linux/uio.h:54
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135b56e)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff81417213)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff8141de0c)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (ffffffff814d4225)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff814df2b1)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff815180b3)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff81229dc8)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81249705)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/block_dev.c (ffffffff8132d45a)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81331720)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/io_uring.c (ffffffff81349c68)
Location: include/linux/uio.h:54
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8136ecbe)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff8142dfa3)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff81434b6c)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/bio.c (ffffffff814ecdd5)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff814f8121)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In lib/iov_iter.c (ffffffff815318a3)
Location: include/linux/uio.h:54
Inline: True
Inline callers:
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
</details>
</li>
</ul>

## Differences
