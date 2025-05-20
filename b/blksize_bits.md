# Function: <code>blksize_bits</code>

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
In fs/buffer.c (ffffffff81242f2c)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8124747d)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:bd_set_size
```
```
In fs/direct-io.c (ffffffff8124a17b)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/buffer.c (ffffffff8126b05a)
Location: include/linux/blkdev.h:1370
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff812706a8)
Location: include/linux/blkdev.h:1370
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81272c67)
Location: include/linux/blkdev.h:1370
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
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
In fs/buffer.c (ffffffff8127e19a)
Location: include/linux/blkdev.h:1575
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff81283e78)
Location: include/linux/blkdev.h:1575
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81286769)
Location: include/linux/blkdev.h:1575
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812b0c74)
Location: include/linux/blkdev.h:1575
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
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
In fs/buffer.c (ffffffff8128bcea)
Location: include/linux/blkdev.h:1600
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff81291538)
Location: include/linux/blkdev.h:1600
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff81293dd6)
Location: include/linux/blkdev.h:1600
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812be03b)
Location: include/linux/blkdev.h:1600
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
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
In fs/buffer.c (ffffffff812ae7ca)
Location: include/linux/blkdev.h:1615
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff812b4288)
Location: include/linux/blkdev.h:1615
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff812b6d36)
Location: include/linux/blkdev.h:1615
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812e193e)
Location: include/linux/blkdev.h:1615
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
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
In fs/buffer.c (ffffffff812d62fa)
Location: include/linux/blkdev.h:1664
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff812db8a8)
Location: include/linux/blkdev.h:1664
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (ffffffff812df744)
Location: include/linux/blkdev.h:1664
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff8130e11f)
Location: include/linux/blkdev.h:1664
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
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
In fs/buffer.c (ffffffff812eb6ca)
Location: include/linux/blkdev.h:1434
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff812f07cc)
Location: include/linux/blkdev.h:1434
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff812f56a3)
Location: include/linux/blkdev.h:1434
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff81323b5d)
Location: include/linux/blkdev.h:1434
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_actor
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
In fs/buffer.c (ffffffff8130cdca)
Location: include/linux/blkdev.h:1448
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8131214a)
Location: include/linux/blkdev.h:1448
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffff8131696d)
Location: include/linux/blkdev.h:1448
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8134da75)
Location: include/linux/blkdev.h:1448
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (ffffffff8131fcaa)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff81325096)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (ffffffff8135a1aa)
Location: include/linux/blkdev.h:1509
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8136040d)
Location: include/linux/blkdev.h:1509
Inline: True
Inline callers:
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (0)
Location: include/linux/blkdev.h:1509
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1509
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (ffffffff813682ca)
Location: include/linux/blkdev.h:1627
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8136d99a)
Location: include/linux/blkdev.h:1627
Inline: True
Inline callers:
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (0)
Location: include/linux/blkdev.h:1627
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1627
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (ffffffff8136ea3a)
Location: include/linux/blkdev.h:1624
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff81374378)
Location: include/linux/blkdev.h:1624
Inline: True
Inline callers:
  - fs/block_dev.c:sb_min_blocksize
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_blocksize
```
```
In fs/direct-io.c (0)
Location: include/linux/blkdev.h:1624
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1624
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (ffffffff813bd71e)
Location: include/linux/blkdev.h:1615
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff813c3abb)
Location: include/linux/blkdev.h:1615
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1615
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/bdev.c (ffffffff815c4108)
Location: include/linux/blkdev.h:1615
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
  - block/bdev.c:set_blocksize
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
In fs/buffer.c (ffffffff814446c1)
Location: include/linux/blkdev.h:1381
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff8144a972)
Location: include/linux/blkdev.h:1381
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1381
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/bdev.c (ffffffff8166f173)
Location: include/linux/blkdev.h:1381
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
  - block/bdev.c:set_blocksize
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
In fs/buffer.c (ffffffff814d3945)
Location: include/linux/blkdev.h:1337
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff814d906a)
Location: include/linux/blkdev.h:1337
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In block/bdev.c (ffffffff8172a4ae)
Location: include/linux/blkdev.h:1337
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
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
In fs/buffer.c (ffffffff81508a1e)
Location: include/linux/blkdev.h:1334
Inline: True
Inline callers:
  - fs/buffer.c:folio_init_buffers
```
```
In fs/direct-io.c (ffffffff81511f05)
Location: include/linux/blkdev.h:1334
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In block/bdev.c (ffffffff817667eb)
Location: include/linux/blkdev.h:1334
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
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
In fs/buffer.c (ffffffff8153d87c)
Location: include/linux/blkdev.h:1314
Inline: True
Inline callers:
  - fs/buffer.c:folio_init_buffers
```
```
In fs/direct-io.c (ffffffff815463cc)
Location: include/linux/blkdev.h:1314
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In block/bdev.c (ffffffff817a831b)
Location: include/linux/blkdev.h:1314
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
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
In fs/buffer.c (ffff8000103d8960)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffff8000103df660)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (c05b2ed4)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (c05b7968)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (c0000000004dc668)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (c0000000004e4494)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (ffffffe000291160)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffe00029649c)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (ffffffe00029a7f2)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffe0002c9d5a)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (ffffffff8131828a)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8131d676)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (ffffffff81308e7a)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8130e216)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (ffffffff81315d5a)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8131b146)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
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
In fs/buffer.c (ffffffff81327a6a)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8132cde6)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/blkdev.h:1475
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
</details>
</li>
</ul>

## Differences
