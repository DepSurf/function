# Function: <code>user_backed_iter</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138f306)
Location: include/linux/uio.h:122
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/direct-io.c (ffffffff814d8d0b)
Location: include/linux/uio.h:122
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff815208a5)
Location: include/linux/uio.h:122
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff8161d620)
Location: include/linux/uio.h:122
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff816265ab)
Location: include/linux/uio.h:122
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/fops.c (ffffffff8172bc8d)
Location: include/linux/uio.h:122
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In lib/iov_iter.c (ffffffff817d2990)
Location: include/linux/uio.h:122
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
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
In mm/shmem.c (ffffffff813c0516)
Location: include/linux/uio.h:144
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/direct-io.c (ffffffff81511a8e)
Location: include/linux/uio.h:144
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81558896)
Location: include/linux/uio.h:144
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff8165575c)
Location: include/linux/uio.h:144
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff8165e991)
Location: include/linux/uio.h:144
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/fops.c (ffffffff81767d8a)
Location: include/linux/uio.h:144
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff8176bc13)
Location: include/linux/uio.h:144
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff817789cc)
Location: include/linux/uio.h:144
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In lib/iov_iter.c (ffffffff818144cf)
Location: include/linux/uio.h:144
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
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
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/direct-io.c (ffffffff81545f39)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8158efcd)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fuse/dev.c (ffffffff8168e4c8)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_write
  - fs/fuse/dev.c:fuse_dev_read
```
```
In fs/fuse/file.c (ffffffff816983e1)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/fops.c (ffffffff817a99e4)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff817ae0b2)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff817bad9e)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In lib/iov_iter.c (ffffffff818594ca)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
