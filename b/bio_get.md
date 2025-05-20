# Function: <code>bio_get</code>

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
In fs/ext4/page-io.c (ffffffff8129fdba)
Location: include/linux/bio.h:282
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_io_submit
```
```
In block/bio.c (ffffffff813b283b)
Location: include/linux/bio.h:282
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff813bf56b)
Location: include/linux/bio.h:282
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
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
In block/bio.c (ffffffff813f5f1b)
Location: include/linux/bio.h:231
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814034bd)
Location: include/linux/bio.h:231
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In fs/block_dev.c (ffffffff8128390d)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In block/bio.c (ffffffff8140f91f)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff8141d21b)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffff8120b89e)
Location: include/linux/bio.h:244
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff81290fd6)
Location: include/linux/bio.h:244
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In block/bio.c (ffffffff8141d313)
Location: include/linux/bio.h:244
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff8142b23b)
Location: include/linux/bio.h:244
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffff81224dc4)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff812b3d04)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In block/bio.c (ffffffff81448123)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814564ab)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffff81247372)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff812dc517)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In block/bio.c (ffffffff8147b349)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff81489921)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffff8125b7d4)
Location: include/linux/bio.h:203
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff812f1d4c)
Location: include/linux/bio.h:203
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
```
```
In block/bio.c (ffffffff814995f7)
Location: include/linux/bio.h:203
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814a375f)
Location: include/linux/bio.h:203
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffff81276920)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff81312718)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff814c7708)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814d18b3)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffff81286410)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff81325667)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff814e05bc)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814eacd3)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffff812b86db)
Location: include/linux/bio.h:224
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff8135fbcb)
Location: include/linux/bio.h:224
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff813aa3f0)
Location: include/linux/bio.h:224
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In block/blk-map.c (ffffffff8154ab42)
Location: include/linux/bio.h:224
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
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
In mm/page_io.c (ffffffff812c3d14)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff8136d448)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff813bba38)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In block/blk-map.c (ffffffff81566727)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
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
In mm/page_io.c (ffffffff812cab19)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff81373ce6)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff813c2b2f)
Location: include/linux/bio.h:238
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
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
In mm/page_io.c (ffffffff8130fb28)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff81412a3f)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In block/fops.c (ffffffff815c5f11)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO
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
In mm/page_io.c (ffffffff8137a548)
Location: include/linux/bio.h:212
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8148971c)
Location: include/linux/bio.h:212
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In block/fops.c (ffffffff81670a41)
Location: include/linux/bio.h:212
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
In mm/page_io.c (ffffffff813f7fec)
Location: include/linux/bio.h:212
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8151d091)
Location: include/linux/bio.h:212
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In block/fops.c (ffffffff8172c0da)
Location: include/linux/bio.h:212
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
In fs/iomap/buffered-io.c (ffffffff81555238)
Location: include/linux/bio.h:214
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In block/fops.c (ffffffff817681bd)
Location: include/linux/bio.h:214
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
In fs/iomap/buffered-io.c (ffffffff8158b50a)
Location: include/linux/bio.h:214
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
```
```
In block/fops.c (ffffffff817a9dfd)
Location: include/linux/bio.h:214
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
In mm/page_io.c (ffff800010320a84)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffff8000103e0e54)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
```
```
In block/bio.c (ffff8000105dd11c)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffff8000105e9820)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (c0539468)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (c05b80c0)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In block/bio.c (c078a5bc)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (c0795b14)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (c0000000003f5d4c)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (c0000000004e6ed0)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
```
```
In block/bio.c (c00000000076e6b4)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (c00000000077e304)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffe00022208a)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffe0002977fe)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
```
```
In block/bio.c (ffffffe00042031a)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffe000429c6c)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffff8127ea60)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff8131dc47)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff814d8b9c)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814e32b3)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffff81270890)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff8130e7e7)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff814c954c)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814d3c33)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffff8127c800)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff8131b717)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff814d4c2c)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814df343)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
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
In mm/page_io.c (ffffffff8128c3d0)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/block_dev.c (ffffffff8132d4f7)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff814ed7dc)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814f81b3)
Location: include/linux/bio.h:216
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
</details>
</li>
</ul>

## Differences
