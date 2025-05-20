# Function: <code>queue_dma_alignment</code>

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
In block/bio.c (ffffffff813b25f7)
Location: include/linux/blkdev.h:1328
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff813bf464)
Location: include/linux/blkdev.h:1328
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_kern
```
```
In drivers/scsi/sg.c (ffffffff815c552c)
Location: include/linux/blkdev.h:1328
Inline: True
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
In block/bio.c (ffffffff813f5c6a)
Location: include/linux/blkdev.h:1357
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814036d9)
Location: include/linux/blkdev.h:1357
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff8161dd24)
Location: include/linux/blkdev.h:1357
Inline: True
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
In block/bio.c (ffffffff8140f67a)
Location: include/linux/blkdev.h:1562
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff8141d447)
Location: include/linux/blkdev.h:1562
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff8164e8e4)
Location: include/linux/blkdev.h:1562
Inline: True
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
In block/bio.c (ffffffff8141d0c0)
Location: include/linux/blkdev.h:1587
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff8142b492)
Location: include/linux/blkdev.h:1587
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff81663145)
Location: include/linux/blkdev.h:1587
Inline: True
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
In block/bio.c (ffffffff81447fc4)
Location: include/linux/blkdev.h:1602
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814566a1)
Location: include/linux/blkdev.h:1602
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff816cc795)
Location: include/linux/blkdev.h:1602
Inline: True
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
In block/bio.c (ffffffff8147b0d5)
Location: include/linux/blkdev.h:1651
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff81489ae8)
Location: include/linux/blkdev.h:1651
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff81709102)
Location: include/linux/blkdev.h:1651
Inline: True
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
In block/bio.c (ffffffff81499385)
Location: include/linux/blkdev.h:1421
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814a3928)
Location: include/linux/blkdev.h:1421
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff8172b5f2)
Location: include/linux/blkdev.h:1421
Inline: True
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
In block/bio.c (ffffffff814c75eb)
Location: include/linux/blkdev.h:1435
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814d1b29)
Location: include/linux/blkdev.h:1435
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff81766cfc)
Location: include/linux/blkdev.h:1435
Inline: True
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
In block/bio.c (ffffffff814e0489)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814eaed9)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff8178acec)
Location: include/linux/blkdev.h:1462
Inline: True
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
In block/blk-map.c (ffffffff81549ec7)
Location: include/linux/blkdev.h:1496
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff8184f33f)
Location: include/linux/blkdev.h:1496
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
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
In block/blk-map.c (ffffffff81565c77)
Location: include/linux/blkdev.h:1614
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff8185fcbf)
Location: include/linux/blkdev.h:1614
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
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
In block/blk-map.c (ffffffff8156e12c)
Location: include/linux/blkdev.h:1611
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff81841d04)
Location: include/linux/blkdev.h:1611
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
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
In block/blk-map.c (ffffffff815d25ec)
Location: include/linux/blkdev.h:1602
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff818ce987)
Location: include/linux/blkdev.h:1602
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
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
In block/blk-map.c (ffffffff8167e309)
Location: include/linux/blkdev.h:1368
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff81a1af9b)
Location: include/linux/blkdev.h:1368
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
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
In fs/iomap/direct-io.c (ffffffff81520353)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff8158086f)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In block/bdev.c (ffffffff8172b0d1)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
```
```
In block/fops.c (ffffffff8172b905)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/blk-sysfs.c (ffffffff817367a9)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_dma_alignment_show
```
```
In block/blk-map.c (ffffffff8173afe9)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff81b9c186)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
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
Location: include/linux/blkdev.h:1309
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff815b7e2c)
Location: include/linux/blkdev.h:1309
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In block/bdev.c (ffffffff8176733e)
Location: include/linux/blkdev.h:1309
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
```
```
In block/fops.c (ffffffff817677a5)
Location: include/linux/blkdev.h:1309
Inline: True
```
```
In block/blk-sysfs.c (ffffffff81772f89)
Location: include/linux/blkdev.h:1309
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_dma_alignment_show
```
```
In block/blk-map.c (ffffffff817778a2)
Location: include/linux/blkdev.h:1309
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff81bf2776)
Location: include/linux/blkdev.h:1309
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
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
Location: include/linux/blkdev.h:1289
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/ext4/inode.c (ffffffff815f0bc0)
Location: include/linux/blkdev.h:1289
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
```
```
In block/bdev.c (ffffffff817a900e)
Location: include/linux/blkdev.h:1289
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
```
```
In block/fops.c (ffffffff817a9595)
Location: include/linux/blkdev.h:1289
Inline: True
```
```
In block/blk-sysfs.c (ffffffff817b52c9)
Location: include/linux/blkdev.h:1289
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_dma_alignment_show
```
```
In block/blk-map.c (ffffffff817b9ac2)
Location: include/linux/blkdev.h:1289
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/bio-integrity.c (ffffffff817f9349)
Location: include/linux/blkdev.h:1289
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_map_user
```
```
In drivers/scsi/sg.c (ffffffff81c48066)
Location: include/linux/blkdev.h:1289
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
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
In block/bio.c (ffff8000105dd008)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffff8000105e960c)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffff8000109902e8)
Location: include/linux/blkdev.h:1462
Inline: True
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
In block/bio.c (c078a4a4)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (c0795d2c)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (c0a63cdc)
Location: include/linux/blkdev.h:1462
Inline: True
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
In block/bio.c (c00000000076e55c)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (c00000000077e620)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (c000000000a54acc)
Location: include/linux/blkdev.h:1462
Inline: True
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
In block/bio.c (ffffffe000420244)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffe000429e4e)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffe0005f5598)
Location: include/linux/blkdev.h:1462
Inline: True
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
In block/bio.c (ffffffff814d8a69)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814e34b9)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff8173f3dc)
Location: include/linux/blkdev.h:1462
Inline: True
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
In block/bio.c (ffffffff814c9419)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814d3e39)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff8172107c)
Location: include/linux/blkdev.h:1462
Inline: True
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
In block/bio.c (ffffffff814d4af9)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814df549)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff8177fb6c)
Location: include/linux/blkdev.h:1462
Inline: True
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
In block/bio.c (ffffffff814ed6a9)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff814f83b9)
Location: include/linux/blkdev.h:1462
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In drivers/scsi/sg.c (ffffffff8179995c)
Location: include/linux/blkdev.h:1462
Inline: True
```
</details>
</li>
</ul>

## Differences
