# Function: <code>is_sync_kiocb</code>

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
In fs/direct-io.c (0)
Location: include/linux/fs.h:331
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/fs.h:331
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:331
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:331
Inline: True
```
```
In fs/fuse/file.c (ffffffff8131634f)
Location: include/linux/fs.h:331
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_aio_complete
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
In fs/direct-io.c (0)
Location: include/linux/fs.h:332
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/fs.h:332
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:332
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:332
Inline: True
```
```
In fs/fuse/file.c (ffffffff8134d89a)
Location: include/linux/fs.h:332
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff81283924)
Location: include/linux/fs.h:282
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:282
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/fs.h:282
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/fs.h:282
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:282
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:282
Inline: True
```
```
In fs/fuse/file.c (ffffffff813631a6)
Location: include/linux/fs.h:282
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff81290ff0)
Location: include/linux/fs.h:301
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:301
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/fs.h:301
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/fs.h:301
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:301
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:301
Inline: True
```
```
In fs/fuse/file.c (ffffffff81377b4a)
Location: include/linux/fs.h:301
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff812b3d1e)
Location: include/linux/fs.h:304
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:304
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/fs.h:304
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/fs.h:304
Inline: True
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:304
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:304
Inline: True
```
```
In fs/fuse/file.c (ffffffff8139c8f1)
Location: include/linux/fs.h:304
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff812dc536)
Location: include/linux/fs.h:307
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:307
Inline: True
```
```
In fs/iomap.c (ffffffff8130f89b)
Location: include/linux/fs.h:307
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:307
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:307
Inline: True
```
```
In fs/fuse/file.c (ffffffff813cbd0d)
Location: include/linux/fs.h:307
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff812f1c91)
Location: include/linux/fs.h:321
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:321
Inline: True
```
```
In fs/iomap.c (ffffffff81326761)
Location: include/linux/fs.h:321
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:321
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:321
Inline: True
```
```
In fs/fuse/file.c (ffffffff813e4dc7)
Location: include/linux/fs.h:321
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff8131263c)
Location: include/linux/fs.h:333
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:333
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134d11e)
Location: include/linux/fs.h:333
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:333
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:333
Inline: True
```
```
In fs/fuse/file.c (ffffffff814106d7)
Location: include/linux/fs.h:333
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff8132558b)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff813653d1)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/fuse/file.c (ffffffff8142a2e7)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff8135fea7)
Location: include/linux/fs.h:337
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8136369c)
Location: include/linux/fs.h:337
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813ad45f)
Location: include/linux/fs.h:337
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/ext4/file.c (ffffffff813e9cf8)
Location: include/linux/fs.h:337
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fuse/file.c (ffffffff8147a348)
Location: include/linux/fs.h:337
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_direct_write_iter
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
In fs/block_dev.c (ffffffff8136d717)
Location: include/linux/fs.h:340
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff813708bf)
Location: include/linux/fs.h:340
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813bea10)
Location: include/linux/fs.h:340
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/ext4/file.c (ffffffff813fbe16)
Location: include/linux/fs.h:340
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fuse/file.c (ffffffff8149503b)
Location: include/linux/fs.h:340
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_direct_write_iter
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
In fs/block_dev.c (ffffffff81373dfc)
Location: include/linux/fs.h:343
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8137718b)
Location: include/linux/fs.h:343
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813c5668)
Location: include/linux/fs.h:343
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/fuse/file.c (ffffffff8149a09b)
Location: include/linux/fs.h:343
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/direct-io.c (ffffffff813c3736)
Location: include/linux/fs.h:345
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81415a69)
Location: include/linux/fs.h:345
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/fuse/file.c (ffffffff814f1adf)
Location: include/linux/fs.h:345
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
```
In block/fops.c (ffffffff815c6021)
Location: include/linux/fs.h:345
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
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
In fs/direct-io.c (ffffffff8144a524)
Location: include/linux/fs.h:334
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8148d215)
Location: include/linux/fs.h:334
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/fuse/file.c (ffffffff8158153f)
Location: include/linux/fs.h:334
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
```
In block/fops.c (ffffffff81670a46)
Location: include/linux/fs.h:334
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
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
In fs/direct-io.c (ffffffff814d8c2f)
Location: include/linux/fs.h:351
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81520775)
Location: include/linux/fs.h:351
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/fuse/file.c (ffffffff8162739f)
Location: include/linux/fs.h:351
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
```
In block/fops.c (ffffffff8172c0de)
Location: include/linux/fs.h:351
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
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
In fs/direct-io.c (ffffffff81511b1a)
Location: include/linux/fs.h:366
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/trace.c (ffffffff81552b12)
Location: include/linux/fs.h:366
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_dio_complete
  - fs/iomap/trace.c:perf_trace_iomap_dio_rw_begin
  - fs/iomap/trace.c:trace_event_raw_event_iomap_dio_complete
  - fs/iomap/trace.c:trace_event_raw_event_iomap_dio_rw_begin
```
```
In fs/iomap/direct-io.c (ffffffff81558791)
Location: include/linux/fs.h:366
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/fuse/file.c (ffffffff8165f75f)
Location: include/linux/fs.h:366
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
```
In block/fops.c (ffffffff817681c1)
Location: include/linux/fs.h:366
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
In fs/direct-io.c (ffffffff81545fb7)
Location: include/linux/fs.h:399
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/backing-file.c (ffffffff81581818)
Location: include/linux/fs.h:399
Inline: True
```
```
In fs/iomap/trace.c (ffffffff81588ad2)
Location: include/linux/fs.h:399
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_dio_complete
  - fs/iomap/trace.c:perf_trace_iomap_dio_rw_begin
  - fs/iomap/trace.c:trace_event_raw_event_iomap_dio_complete
  - fs/iomap/trace.c:trace_event_raw_event_iomap_dio_rw_begin
```
```
In fs/iomap/direct-io.c (ffffffff8158ee91)
Location: include/linux/fs.h:399
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/fuse/file.c (ffffffff816995ce)
Location: include/linux/fs.h:399
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_direct_write_iter
```
```
In block/fops.c (ffffffff817a9e01)
Location: include/linux/fs.h:399
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
In fs/block_dev.c (ffff8000103e0d84)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/iomap/direct-io.c (ffff80001042d0fc)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/fuse/file.c (ffff80001050e2ac)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (c05b9834)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (c05bcbd4)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (c05f6118)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/ext4/file.c (c06320b8)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (c0649878)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/fuse/file.c (c06c9958)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/block_dev.c (c0000000004e6dd4)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/iomap/direct-io.c (c00000000053d6a0)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/fuse/file.c (c00000000065521c)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffe00029775a)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffe0002c979e)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/fuse/file.c (ffffffe000378f3a)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff8131db6b)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135d9b1)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/fuse/file.c (ffffffff814228c7)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff8130e70b)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134e651)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/fuse/file.c (ffffffff81413347)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff8131b63b)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135b481)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/fuse/file.c (ffffffff8141ea67)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
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
In fs/block_dev.c (ffffffff8132d41b)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/direct-io.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8136ebd1)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/file.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fs.h:335
Inline: True
```
```
In fs/fuse/file.c (ffffffff814357c7)
Location: include/linux/fs.h:335
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
```
</details>
</li>
</ul>

## Differences
