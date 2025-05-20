# Function: <code>generic_write_sync</code>

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
In mm/filemap.c (ffffffff8118f4b9)
Location: include/linux/fs.h:2447
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff81247e7c)
Location: include/linux/fs.h:2447
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_iter
```
```
In fs/direct-io.c (ffffffff81249a3a)
Location: include/linux/fs.h:2447
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/ext4/file.c (ffffffff812920c1)
Location: include/linux/fs.h:2447
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In mm/filemap.c (ffffffff811a2aa1)
Location: include/linux/fs.h:2556
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff81270bc3)
Location: include/linux/fs.h:2556
Inline: True
```
```
In fs/direct-io.c (ffffffff812723fd)
Location: include/linux/fs.h:2556
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/ext4/file.c (ffffffff812bf645)
Location: include/linux/fs.h:2556
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In mm/filemap.c (ffffffff811b28e1)
Location: include/linux/fs.h:2525
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff81284533)
Location: include/linux/fs.h:2525
Inline: True
```
```
In fs/direct-io.c (ffffffff81285f73)
Location: include/linux/fs.h:2525
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap.c (ffffffff812b10b1)
Location: include/linux/fs.h:2525
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_complete_work
```
```
In fs/ext4/file.c (ffffffff812d53ab)
Location: include/linux/fs.h:2525
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In mm/filemap.c (ffffffff811b9559)
Location: include/linux/fs.h:2637
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff81291b4c)
Location: include/linux/fs.h:2637
Inline: True
```
```
In fs/direct-io.c (ffffffff812935d3)
Location: include/linux/fs.h:2637
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap.c (ffffffff812be471)
Location: include/linux/fs.h:2637
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_complete_work
```
```
In fs/ext4/file.c (ffffffff812f1c1d)
Location: include/linux/fs.h:2637
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In mm/filemap.c (ffffffff811cf9d9)
Location: include/linux/fs.h:2698
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff812b48be)
Location: include/linux/fs.h:2698
Inline: True
```
```
In fs/direct-io.c (ffffffff812b64b7)
Location: include/linux/fs.h:2698
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap.c (ffffffff812e1e11)
Location: include/linux/fs.h:2698
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_complete_work
```
```
In fs/ext4/file.c (ffffffff813162b7)
Location: include/linux/fs.h:2698
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (ffffffff8139d361)
Location: include/linux/fs.h:2698
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff811f0b10)
Location: include/linux/fs.h:2721
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff812dbe00)
Location: include/linux/fs.h:2721
Inline: True
```
```
In fs/direct-io.c (ffffffff812df43f)
Location: include/linux/fs.h:2721
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap.c (ffffffff8130e57d)
Location: include/linux/fs.h:2721
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff81344112)
Location: include/linux/fs.h:2721
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (ffffffff813cc77b)
Location: include/linux/fs.h:2721
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff812012d0)
Location: include/linux/fs.h:2805
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff812f14f0)
Location: include/linux/fs.h:2805
Inline: True
```
```
In fs/direct-io.c (ffffffff812f3f1e)
Location: include/linux/fs.h:2805
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap.c (ffffffff81323dad)
Location: include/linux/fs.h:2805
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff8135c273)
Location: include/linux/fs.h:2805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (ffffffff813e5aab)
Location: include/linux/fs.h:2805
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff81218ec8)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff81313382)
Location: include/linux/fs.h:2811
Inline: True
```
```
In fs/direct-io.c (ffffffff81315899)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8134d091)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff8138530e)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (ffffffff81411a3d)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff812267c1)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff813262ad)
Location: include/linux/fs.h:2873
Inline: True
```
```
In fs/direct-io.c (ffffffff81328719)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff81365342)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff8139dd9d)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (ffffffff8142b72d)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff81251751)
Location: include/linux/fs.h:2908
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff8135f167)
Location: include/linux/fs.h:2908
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_iter
```
```
In fs/direct-io.c (ffffffff81361eda)
Location: include/linux/fs.h:2908
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff813ad3d2)
Location: include/linux/fs.h:2908
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff813e91b3)
Location: include/linux/fs.h:2908
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/fuse/file.c (ffffffff8147b346)
Location: include/linux/fs.h:2908
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_cache_write_iter
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
In mm/filemap.c (ffffffff8125cea4)
Location: include/linux/fs.h:2743
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff8136c9b4)
Location: include/linux/fs.h:2743
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_iter
```
```
In fs/direct-io.c (ffffffff8136f1ca)
Location: include/linux/fs.h:2743
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff813be3c7)
Location: include/linux/fs.h:2743
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff813fb5b3)
Location: include/linux/fs.h:2743
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/fuse/file.c (ffffffff81496145)
Location: include/linux/fs.h:2743
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In fs/fuse/dax.c (ffffffff8149df7b)
Location: include/linux/fs.h:2743
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
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
In mm/filemap.c (ffffffff81261b24)
Location: include/linux/fs.h:2979
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff8137322a)
Location: include/linux/fs.h:2979
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_iter
```
```
In fs/direct-io.c (ffffffff81375a7a)
Location: include/linux/fs.h:2979
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff813c5407)
Location: include/linux/fs.h:2979
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff81401a83)
Location: include/linux/fs.h:2979
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/fuse/file.c (ffffffff8149b1d5)
Location: include/linux/fs.h:2979
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In fs/fuse/dax.c (ffffffff814a3f4b)
Location: include/linux/fs.h:2979
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
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
In mm/filemap.c (ffffffff8129a434)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/direct-io.c (ffffffff813c1dcd)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff814151aa)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff81454013)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/fuse/file.c (ffffffff814f2c15)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In fs/fuse/dax.c (ffffffff814fbf55)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff815c589e)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
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
In mm/filemap.c (ffffffff812f7460)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/direct-io.c (ffffffff81448c49)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8148c7fc)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff814d159b)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/fuse/file.c (ffffffff8158261b)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In fs/fuse/dax.c (ffffffff8158c4b5)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff816703ac)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
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
In mm/filemap.c (ffffffff81360d10)
Location: include/linux/fs.h:2882
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/direct-io.c (ffffffff814d759a)
Location: include/linux/fs.h:2882
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff81520f5c)
Location: include/linux/fs.h:2882
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff8156a36f)
Location: include/linux/fs.h:2882
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/fuse/file.c (ffffffff81628476)
Location: include/linux/fs.h:2882
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In fs/fuse/dax.c (ffffffff81632d2a)
Location: include/linux/fs.h:2882
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff8172bac6)
Location: include/linux/fs.h:2882
Inline: True
Inline callers:
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
In mm/filemap.c (ffffffff813930d0)
Location: include/linux/fs.h:2496
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/direct-io.c (ffffffff81510585)
Location: include/linux/fs.h:2496
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff81558fa3)
Location: include/linux/fs.h:2496
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff815a22d2)
Location: include/linux/fs.h:2496
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/fuse/file.c (ffffffff81660772)
Location: include/linux/fs.h:2496
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In fs/fuse/dax.c (ffffffff8166afdd)
Location: include/linux/fs.h:2496
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff8176790e)
Location: include/linux/fs.h:2496
Inline: True
Inline callers:
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
In mm/filemap.c (ffffffff813bcd80)
Location: include/linux/fs.h:2731
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/direct-io.c (ffffffff81544a25)
Location: include/linux/fs.h:2731
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8158f6e3)
Location: include/linux/fs.h:2731
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff815daffb)
Location: include/linux/fs.h:2731
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/fuse/file.c (ffffffff8169a5d2)
Location: include/linux/fs.h:2731
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In fs/fuse/dax.c (ffffffff816a531d)
Location: include/linux/fs.h:2731
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In block/fops.c (ffffffff817aa373)
Location: include/linux/fs.h:2731
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_iter
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
In mm/filemap.c (ffff8000102b3b10)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffff8000103e0588)
Location: include/linux/fs.h:2873
Inline: True
```
```
In fs/direct-io.c (ffff8000103e3bd4)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffff80001042d070)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffff800010471304)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (ffff80001050f560)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (c04e0d8c)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (c05b9fe4)
Location: include/linux/fs.h:2873
Inline: True
```
```
In fs/direct-io.c (c05bb908)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (c05f5f00)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (c06321b0)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (c06cae14)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (c00000000036a8e4)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (c0000000004e6470)
Location: include/linux/fs.h:2873
Inline: True
```
```
In fs/direct-io.c (c0000000004e9b10)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (c00000000053d620)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (c000000000591c78)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (c000000000656afc)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffe0001d909c)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffe0002972d6)
Location: include/linux/fs.h:2873
Inline: True
```
```
In fs/direct-io.c (ffffffe000299a8c)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffe0002c9732)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffe0002fd65c)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (ffffffe000379ef2)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff8121ee11)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff8131e88d)
Location: include/linux/fs.h:2873
Inline: True
```
```
In fs/direct-io.c (ffffffff81320cf9)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8135d922)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff8139637d)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (ffffffff81423d0d)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff81211fd1)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff8130f42d)
Location: include/linux/fs.h:2873
Inline: True
```
```
In fs/direct-io.c (ffffffff81311899)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8134e5c2)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff81386e0d)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (ffffffff8141478d)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff8121cbb1)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff8131c35d)
Location: include/linux/fs.h:2873
Inline: True
```
```
In fs/direct-io.c (ffffffff8131e7c9)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8135b3f2)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff81393cdd)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (ffffffff8141fead)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff8122bc41)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In fs/block_dev.c (ffffffff8132e55d)
Location: include/linux/fs.h:2873
Inline: True
```
```
In fs/direct-io.c (ffffffff813304c9)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8136eb42)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/file.c (ffffffff813a7d6d)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/fuse/file.c (ffffffff81436c2d)
Location: include/linux/fs.h:2873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
</details>
</li>
</ul>

## Differences
