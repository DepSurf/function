# Function: <code>blk_wake_io_task</code>

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
In mm/page_io.c (ffffffff8125af0e)
Location: include/linux/blkdev.h:1768
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffffffff812f16f8)
Location: include/linux/blkdev.h:1768
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap.c (ffffffff81324e12)
Location: include/linux/blkdev.h:1768
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
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
In mm/page_io.c (ffffffff81275f18)
Location: include/linux/blkdev.h:1792
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffffffff81312a7a)
Location: include/linux/blkdev.h:1792
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (ffffffff8134d57e)
Location: include/linux/blkdev.h:1792
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (ffffffff812859e8)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffffffff813259ba)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (ffffffff8136583e)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (ffffffff812b7d91)
Location: include/linux/blkdev.h:1885
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffffffff8135ed6e)
Location: include/linux/blkdev.h:1885
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (ffffffff813adb69)
Location: include/linux/blkdev.h:1885
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (ffffffff812c3441)
Location: include/linux/blkdev.h:1939
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffffffff8136c54e)
Location: include/linux/blkdev.h:1939
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (ffffffff813bf1d9)
Location: include/linux/blkdev.h:1939
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (ffffffff812ca285)
Location: include/linux/blkdev.h:1935
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffffffff81372e7e)
Location: include/linux/blkdev.h:1935
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (ffffffff813c6319)
Location: include/linux/blkdev.h:1935
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (ffffffff8130f2a5)
Location: include/linux/blkdev.h:1933
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/iomap/direct-io.c (ffffffff81416187)
Location: include/linux/blkdev.h:1933
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In block/fops.c (ffffffff815c52fe)
Location: include/linux/blkdev.h:1933
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:blkdev_bio_end_io_simple
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
In mm/page_io.c (ffffffff813794bf)
Location: include/linux/blkdev.h:1473
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/iomap/direct-io.c (ffffffff8148da22)
Location: include/linux/blkdev.h:1473
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In block/fops.c (ffffffff8166fde0)
Location: include/linux/blkdev.h:1473
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io
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
In mm/page_io.c (ffffffff813f6edf)
Location: include/linux/blkdev.h:1424
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/iomap/direct-io.c (ffffffff815211e2)
Location: include/linux/blkdev.h:1424
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In block/fops.c (ffffffff8172b2c0)
Location: include/linux/blkdev.h:1424
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io
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
In fs/iomap/direct-io.c (ffffffff81559215)
Location: include/linux/blkdev.h:1416
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In block/fops.c (ffffffff81767bcf)
Location: include/linux/blkdev.h:1416
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io
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
In fs/iomap/direct-io.c (ffffffff8158f9ab)
Location: include/linux/blkdev.h:1396
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In block/fops.c (ffffffff817a982f)
Location: include/linux/blkdev.h:1396
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io
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
In mm/page_io.c (ffff8000103200e4)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffff8000103e11e8)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (ffff80001042d51c)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (c0538934)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (c05b8500)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (c05f5ff8)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (c0000000003f4f88)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (c0000000004e4e3c)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (c00000000053dc5c)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (ffffffe0002217e4)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffffffe000296970)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (ffffffe0002c9b0a)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (ffffffff8127e038)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffffffff8131df9a)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (ffffffff8135de1e)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (ffffffff8126fe68)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffffffff8130eb3a)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (ffffffff8134eabe)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (ffffffff8127bdd8)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffffffff8131ba6a)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (ffffffff8135b8ee)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
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
In mm/page_io.c (ffffffff8128b9b8)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/block_dev.c (ffffffff8132d84a)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/iomap/direct-io.c (ffffffff8136f03e)
Location: include/linux/blkdev.h:1823
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
</details>
</li>
</ul>

## Differences
