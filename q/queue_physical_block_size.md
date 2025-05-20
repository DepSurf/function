# Function: <code>queue_physical_block_size</code>

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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1205
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1205
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1205
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1234
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1234
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1234
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1399
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1399
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1399
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1437
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1437
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1437
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1452
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1452
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1452
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1492
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1492
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1492
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1271
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1271
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1271
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1285
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1285
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1285
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1312
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
In block/blk-sysfs.c (ffffffff81546bf5)
Location: include/linux/blkdev.h:1346
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_physical_block_size_show
```
```
In block/blk-merge.c (ffffffff8154b6c5)
Location: include/linux/blkdev.h:1346
Inline: True
Inline callers:
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/ioctl.c (ffffffff81557df1)
Location: include/linux/blkdev.h:1346
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff817ea43a)
Location: include/linux/blkdev.h:1346
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In block/blk-sysfs.c (ffffffff815628e9)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_physical_block_size_show
```
```
In block/blk-merge.c (ffffffff81567015)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/ioctl.c (ffffffff815743f1)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff817fee95)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In block/blk-sysfs.c (ffffffff8156af99)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_physical_block_size_show
```
```
In block/blk-merge.c (ffffffff8156f337)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/ioctl.c (ffffffff8157c481)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff817e0467)
Location: include/linux/blkdev.h:1432
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_config_discard
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
In block/blk-sysfs.c (ffffffff815cf209)
Location: include/linux/blkdev.h:1407
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_physical_block_size_show
```
```
In block/blk-merge.c (ffffffff815d39d7)
Location: include/linux/blkdev.h:1407
Inline: True
Inline callers:
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/ioctl.c (ffffffff815e1dd1)
Location: include/linux/blkdev.h:1407
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff8186c358)
Location: include/linux/blkdev.h:1407
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_config_discard
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
In block/blk-sysfs.c (ffffffff8167a7b9)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_physical_block_size_show
```
```
In block/blk-merge.c (ffffffff8167f804)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/ioctl.c (ffffffff81690b7b)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff819b5d7c)
Location: include/linux/blkdev.h:1229
Inline: True
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
In block/blk-sysfs.c (ffffffff81736d39)
Location: include/linux/blkdev.h:1177
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_physical_block_size_show
```
```
In block/ioctl.c (ffffffff8174f75d)
Location: include/linux/blkdev.h:1177
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff81b2aeac)
Location: include/linux/blkdev.h:1177
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
In block/blk-sysfs.c (ffffffff817734f9)
Location: include/linux/blkdev.h:1158
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_physical_block_size_show
```
```
In block/ioctl.c (ffffffff8178b713)
Location: include/linux/blkdev.h:1158
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff81b7b19c)
Location: include/linux/blkdev.h:1158
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
In block/blk-sysfs.c (ffffffff817b57d9)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_physical_block_size_show
```
```
In block/ioctl.c (ffffffff817cde73)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff81bcef8c)
Location: include/linux/blkdev.h:1143
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1312
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
In block/blk-sysfs.c (c07928cc)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_physical_block_size_show
```
```
In block/blk-merge.c (c0796a60)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/ioctl.c (c07a4024)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
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
In block/blk-sysfs.c (c000000000779b3c)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_physical_block_size_show
```
```
In block/blk-merge.c (c00000000077f3d0)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/ioctl.c (c000000000791030)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/compat_ioctl.c (c0000000007bacd8)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
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
In block/blk-sysfs.c (ffffffe000426cec)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_physical_block_size_show
```
```
In block/blk-merge.c (ffffffe00042a790)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/ioctl.c (ffffffe000435790)
Location: include/linux/blkdev.h:1312
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1312
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1312
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1312
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
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
```
In block/compat_ioctl.c (0)
Location: include/linux/blkdev.h:1312
Inline: True
```
</details>
</li>
</ul>

## Differences
