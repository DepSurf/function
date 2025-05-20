# Function: <code>iov_iter_rw</code>

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
In fs/splice.c (ffffffff812e6768)
Location: include/linux/uio.h:82
Inline: True
```
```
In fs/block_dev.c (ffffffff812f1c16)
Location: include/linux/uio.h:82
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812f4283)
Location: include/linux/uio.h:82
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8130c0cc)
Location: include/linux/uio.h:82
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap.c (ffffffff81326835)
Location: include/linux/uio.h:82
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff81370f0c)
Location: include/linux/uio.h:82
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/inode.c (ffffffff813c74fd)
Location: include/linux/uio.h:82
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff813e4cf2)
Location: include/linux/uio.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/bio.c (ffffffff81499149)
Location: include/linux/uio.h:82
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff814da481)
Location: include/linux/uio.h:82
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffff813053ea)
Location: include/linux/uio.h:84
Inline: True
```
```
In fs/block_dev.c (ffffffff813125c3)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff813169b3)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff813333d9)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (ffffffff8134d1fa)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff8139a8b1)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/inode.c (ffffffff813f1fed)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff814105f1)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/bio.c (ffffffff814c734e)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff81505cbc)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffff8131847a)
Location: include/linux/uio.h:84
Inline: True
```
```
In fs/block_dev.c (ffffffff81325513)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81329831)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81346f8a)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (ffffffff813654ac)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff813b3389)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/inode.c (ffffffff8140beed)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff8142a201)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/bio.c (ffffffff814e01e6)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff81523c9c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffff81351341)
Location: include/linux/uio.h:84
Inline: True
```
```
In fs/block_dev.c (ffffffff8135fa8a)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81363629)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8138c65a)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (ffffffff813ad519)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/fat/inode.c (ffffffff81459ded)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff8147a29d)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/blk-map.c (ffffffff8154a3ed)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff815870c8)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffff8135de73)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/block_dev.c (ffffffff8136d30a)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff813707c5)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8139dd8a)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (ffffffff813beaba)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fat/inode.c (ffffffff8147613d)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff81494f8d)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In fs/fuse/dax.c (ffffffff8149def8)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/blk-map.c (ffffffff81566192)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff815a48a8)
Location: include/linux/uio.h:83
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffff81364ce6)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/block_dev.c (ffffffff81373b88)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8137709b)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff813a4f9a)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (ffffffff813c5738)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fat/inode.c (ffffffff8147bbad)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff81499fed)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In fs/fuse/dax.c (ffffffff814a3ecf)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/blk-map.c (ffffffff8156e67d)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff815ae049)
Location: include/linux/uio.h:91
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffff813b31ba)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/direct-io.c (ffffffff813c3673)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff813f4b13)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
```
```
In fs/iomap/direct-io.c (ffffffff81415b32)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fat/inode.c (ffffffff814d32ea)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff814f1a12)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In fs/fuse/dax.c (ffffffff814fbf8d)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff815c5db5)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-map.c (ffffffff815d2c93)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff81615b0d)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffff814382e1)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/direct-io.c (ffffffff8144a43c)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81468201)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
```
```
In fs/iomap/direct-io.c (ffffffff8148d316)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fat/inode.c (ffffffff815606ba)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff81581479)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In fs/fuse/dax.c (ffffffff8158c4ff)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff8167053e)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-map.c (ffffffff8167e91a)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff816e265c)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/direct-io.c (ffffffff814d8b4b)
Location: include/linux/uio.h:117
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/dax.c (ffffffff814f85a7)
Location: include/linux/uio.h:117
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
```
```
In fs/iomap/direct-io.c (ffffffff81520876)
Location: include/linux/uio.h:117
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fat/inode.c (ffffffff81602bea)
Location: include/linux/uio.h:117
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff816272d9)
Location: include/linux/uio.h:117
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In fs/fuse/dax.c (ffffffff81632dad)
Location: include/linux/uio.h:117
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff8172bb6e)
Location: include/linux/uio.h:117
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-map.c (ffffffff8173b6c6)
Location: include/linux/uio.h:117
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff817d29a4)
Location: include/linux/uio.h:117
Inline: True
Inline callers:
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
In fs/direct-io.c (ffffffff81511a20)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8152fe57)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
```
```
In fs/iomap/direct-io.c (ffffffff8155886f)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fat/inode.c (ffffffff8163ab0a)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff8165f699)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In fs/fuse/dax.c (ffffffff8166b063)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff81767c59)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-map.c (ffffffff81777e06)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff81813420)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
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
In fs/direct-io.c (ffffffff81545ec1)
Location: include/linux/uio.h:134
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81564d37)
Location: include/linux/uio.h:134
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
```
```
In fs/iomap/direct-io.c (ffffffff8158ef96)
Location: include/linux/uio.h:134
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/fat/inode.c (ffffffff8167403a)
Location: include/linux/uio.h:134
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff816994d9)
Location: include/linux/uio.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In fs/fuse/dax.c (ffffffff816a53a3)
Location: include/linux/uio.h:134
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff817a98ba)
Location: include/linux/uio.h:134
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/blk-map.c (ffffffff817ba1a2)
Location: include/linux/uio.h:134
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff81858fb8)
Location: include/linux/uio.h:134
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
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
In fs/splice.c (ffff8000103ce558)
Location: include/linux/uio.h:84
Inline: True
```
```
In fs/block_dev.c (ffff8000103e0d38)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffff8000103e4c8c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffff800010407290)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (ffff80001042d1a4)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffff800010487bcc)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/inode.c (ffff8000104ec800)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffff80001050e220)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/bio.c (ffff8000105dcd40)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffff80001062dc04)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (c05a9d38)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/block_dev.c (c05b7f4c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (c05bcb2c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (c05f6200)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (c0649d7c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/inode.c (c06a962c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (c06c9868)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/bio.c (c078a214)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (c07d4c2c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (c0000000004d1930)
Location: include/linux/uio.h:84
Inline: True
```
```
In fs/block_dev.c (c0000000004e6d50)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (c0000000004eafc4)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (c000000000512a80)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (c00000000053d7a0)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (c0000000005ae2a0)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/inode.c (c000000000629aa8)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (c000000000655178)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/bio.c (c00000000076e198)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (c0000000007d112c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffe00028b5ca)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
```
```
In fs/block_dev.c (ffffffe0002976d6)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffe00029a826)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffe0002b217a)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (ffffffe0002c982a)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffe00030f4f8)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/inode.c (ffffffe00035bf0a)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffe000378eb4)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/bio.c (ffffffe00041ffca)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffe00045d8aa)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffff81310a5a)
Location: include/linux/uio.h:84
Inline: True
```
```
In fs/block_dev.c (ffffffff8131daf3)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81321e11)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8133f56a)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (ffffffff8135da8c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff813ab969)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/inode.c (ffffffff814044cd)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff814227e1)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/bio.c (ffffffff814d87c6)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff8151c27c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffff8130166a)
Location: include/linux/uio.h:84
Inline: True
```
```
In fs/block_dev.c (ffffffff8130e693)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff813129b1)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8133022a)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (ffffffff8134e72c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff8139c3f9)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/inode.c (ffffffff813f4f4d)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff81413261)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/bio.c (ffffffff814c9176)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff8150c56c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffff8130e84a)
Location: include/linux/uio.h:84
Inline: True
```
```
In fs/block_dev.c (ffffffff8131b5c3)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8131f8e1)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8133d03a)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (ffffffff8135b55c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff813a91c9)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/inode.c (ffffffff8140184d)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff8141e981)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/bio.c (ffffffff814d4856)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff8151830c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
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
In fs/splice.c (ffffffff8132004a)
Location: include/linux/uio.h:84
Inline: True
```
```
In fs/block_dev.c (ffffffff8132d3a3)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81331601)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8135074a)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/direct-io.c (ffffffff8136ecac)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff813bda79)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/fat/inode.c (ffffffff8141797d)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
```
In fs/fuse/file.c (ffffffff814356e1)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/bio.c (ffffffff814ed406)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_copy_user_iov
```
```
In lib/iov_iter.c (ffffffff81531b8c)
Location: include/linux/uio.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
</details>
</li>
</ul>

## Differences
