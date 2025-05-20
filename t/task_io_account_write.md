# Function: <code>task_io_account_write</code>

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
In mm/page-writeback.c (ffffffff8119a8e5)
Location: include/linux/task_io_accounting_ops.h:24
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/direct-io.c (ffffffff8124a4c4)
Location: include/linux/task_io_accounting_ops.h:24
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
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
In mm/page-writeback.c (ffffffff811af1fd)
Location: include/linux/task_io_accounting_ops.h:24
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/direct-io.c (ffffffff81272e86)
Location: include/linux/task_io_accounting_ops.h:24
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
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
In mm/page-writeback.c (ffffffff811bf89d)
Location: include/linux/task_io_accounting_ops.h:24
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff81283992)
Location: include/linux/task_io_accounting_ops.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81286998)
Location: include/linux/task_io_accounting_ops.h:24
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812b0dba)
Location: include/linux/task_io_accounting_ops.h:24
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
In mm/page-writeback.c (ffffffff811c7a6a)
Location: include/linux/task_io_accounting_ops.h:24
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff81291061)
Location: include/linux/task_io_accounting_ops.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81294030)
Location: include/linux/task_io_accounting_ops.h:24
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812be1a1)
Location: include/linux/task_io_accounting_ops.h:24
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
In mm/page-writeback.c (ffffffff811dc8aa)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff812b3e9b)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812b70c9)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812e1ab9)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff811fc8f7)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff812dc6b0)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812dfa85)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff8130e1e9)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff8120f453)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff812f1e23)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812f500f)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff81323a01)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff81221458)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff813127e9)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81316bed)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8134d946)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff8122eee8)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff81325738)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81329a6b)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81365c04)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff8125bfb1)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff8135fc9a)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8136385c)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813ad059)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff812663b9)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff8136d516)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8136fe76)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/iomap/direct-io.c (ffffffff813be746)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff8126aeb9)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff81373dc5)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81376712)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/iomap/direct-io.c (ffffffff813c5e21)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff812a4b59)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/direct-io.c (ffffffff813c2d2e)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/iomap/direct-io.c (ffffffff814157e2)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/fops.c (ffffffff815c5fec)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff812ff353)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In fs/direct-io.c (ffffffff8144962a)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8148cf0e)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/fops.c (ffffffff8167061e)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
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
In mm/page-writeback.c (ffffffff813679c4)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In fs/direct-io.c (ffffffff814d7d1a)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff81520420)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/fops.c (ffffffff8172bc39)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff81399e64)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In fs/direct-io.c (ffffffff8151128c)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff815583de)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/fops.c (ffffffff81767d21)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff813c3b21)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In fs/direct-io.c (ffffffff8154572c)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8158eadd)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In block/fops.c (ffffffff817a997e)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
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
In mm/page-writeback.c (ffff8000102be154)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffff8000103e0f38)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffff8000103e4e64)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffff80001042caa0)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (c04ea428)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (c05b81c8)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (c05bcda0)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (c05f56f8)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (c000000000376fc0)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (c0000000004e6fb8)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (c0000000004eb1f8)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (c00000000053e18c)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffe0001e0c2c)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffe000297798)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffe00029ae08)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffe0002c9e68)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff81227538)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff8131dd18)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8132204b)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8135e1e4)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff8121a6a8)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff8130e8b8)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81312beb)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8134ee84)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff812252d8)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff8131b7e8)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8131fb1b)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8135bcb4)
Location: include/linux/task_io_accounting_ops.h:25
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
In mm/page-writeback.c (ffffffff812345b8)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/block_dev.c (ffffffff8132d5c8)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff8133183b)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8136f404)
Location: include/linux/task_io_accounting_ops.h:25
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
</details>
</li>
</ul>

## Differences
