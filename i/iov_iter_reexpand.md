# Function: <code>iov_iter_reexpand</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813ad1dc)
Location: include/linux/uio.h:260
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/fuse/file.c (ffffffff8147a3a9)
Location: include/linux/uio.h:260
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/iomap/direct-io.c (ffffffff813be8cc)
Location: include/linux/uio.h:259
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/fuse/file.c (ffffffff8149509c)
Location: include/linux/uio.h:259
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff813732ea)
Location: include/linux/uio.h:269
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/block_dev.c:blkdev_write_iter
```
```
In fs/iomap/direct-io.c (ffffffff813c5e97)
Location: include/linux/uio.h:269
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/fuse/file.c (ffffffff8149a0fc)
Location: include/linux/uio.h:269
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/iomap/direct-io.c (ffffffff81415854)
Location: include/linux/uio.h:280
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/fuse/file.c (ffffffff814f1b78)
Location: include/linux/uio.h:280
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/fops.c (ffffffff815c595a)
Location: include/linux/uio.h:280
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
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
In fs/iomap/direct-io.c (ffffffff8148ce40)
Location: include/linux/uio.h:271
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/fuse/file.c (ffffffff815815cf)
Location: include/linux/uio.h:271
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/fops.c (ffffffff81670e92)
Location: include/linux/uio.h:271
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
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
In fs/iomap/direct-io.c (ffffffff81520358)
Location: include/linux/uio.h:295
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/fuse/file.c (ffffffff8162742f)
Location: include/linux/uio.h:295
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/fops.c (ffffffff8172c5c2)
Location: include/linux/uio.h:295
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
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
In fs/iomap/direct-io.c (ffffffff81558535)
Location: include/linux/uio.h:316
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/fuse/file.c (ffffffff8165f7f2)
Location: include/linux/uio.h:316
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/fops.c (ffffffff81768638)
Location: include/linux/uio.h:316
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
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
In fs/iomap/direct-io.c (ffffffff8158ea24)
Location: include/linux/uio.h:304
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/fuse/file.c (ffffffff81699661)
Location: include/linux/uio.h:304
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
```
In block/fops.c (ffffffff817aa578)
Location: include/linux/uio.h:304
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
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
