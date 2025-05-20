# Function: <code>bdev_dma_alignment</code>

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
In fs/iomap/direct-io.c (ffffffff81520353)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff81580868)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In block/bdev.c (ffffffff8172b0ca)
Location: include/linux/blkdev.h:1317
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
```
```
In block/fops.c (ffffffff8172b905)
Location: include/linux/blkdev.h:1317
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
In fs/iomap/direct-io.c (ffffffff815584f9)
Location: include/linux/blkdev.h:1314
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff815b7e28)
Location: include/linux/blkdev.h:1314
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In block/bdev.c (ffffffff8176733a)
Location: include/linux/blkdev.h:1314
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
```
```
In block/fops.c (ffffffff817677a5)
Location: include/linux/blkdev.h:1314
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
In fs/iomap/direct-io.c (ffffffff8158e9fb)
Location: include/linux/blkdev.h:1294
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff815f0bbc)
Location: include/linux/blkdev.h:1294
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In block/bdev.c (ffffffff817a900a)
Location: include/linux/blkdev.h:1294
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
```
```
In block/fops.c (ffffffff817a9595)
Location: include/linux/blkdev.h:1294
Inline: True
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
