# Function: <code>iocb_is_dsync</code>

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
In mm/filemap.c (ffffffff81360d15)
Location: include/linux/fs.h:2871
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/direct-io.c (ffffffff814d940e)
Location: include/linux/fs.h:2871
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff81520949)
Location: include/linux/fs.h:2871
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff8156a372)
Location: include/linux/fs.h:2871
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/fuse/file.c (ffffffff81628479)
Location: include/linux/fs.h:2871
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In fs/fuse/dax.c (ffffffff81632d2e)
Location: include/linux/fs.h:2871
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff8172bac9)
Location: include/linux/fs.h:2871
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_iter
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
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
In mm/filemap.c (ffffffff813930d5)
Location: include/linux/fs.h:2485
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/direct-io.c (ffffffff81512122)
Location: include/linux/fs.h:2485
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff815589fa)
Location: include/linux/fs.h:2485
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff815a22d5)
Location: include/linux/fs.h:2485
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/fuse/file.c (ffffffff81660777)
Location: include/linux/fs.h:2485
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In fs/fuse/dax.c (ffffffff8166afe1)
Location: include/linux/fs.h:2485
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff81767911)
Location: include/linux/fs.h:2485
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_iter
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
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
In mm/filemap.c (ffffffff813bcd85)
Location: include/linux/fs.h:2720
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/direct-io.c (ffffffff81546618)
Location: include/linux/fs.h:2720
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8158f140)
Location: include/linux/fs.h:2720
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff815daffe)
Location: include/linux/fs.h:2720
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/fuse/file.c (ffffffff8169a5d7)
Location: include/linux/fs.h:2720
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In fs/fuse/dax.c (ffffffff816a5321)
Location: include/linux/fs.h:2720
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff817aa378)
Location: include/linux/fs.h:2720
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_iter
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
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
