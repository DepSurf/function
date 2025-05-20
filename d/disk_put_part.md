# Function: <code>disk_put_part</code>

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
In fs/block_dev.c (ffffffff81248729)
Location: include/linux/genhd.h:278
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff813c8bc3)
Location: include/linux/genhd.h:278
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff813c99a5)
Location: include/linux/genhd.h:278
Inline: True
Inline callers:
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:set_disk_ro
  - block/genhd.c:bdget_disk
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:add_disk
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
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
In fs/block_dev.c (ffffffff8127115f)
Location: include/linux/genhd.h:262
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff8140ce23)
Location: include/linux/genhd.h:262
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff8140e012)
Location: include/linux/genhd.h:262
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff81284acc)
Location: include/linux/genhd.h:253
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff81428103)
Location: include/linux/genhd.h:253
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff814293a2)
Location: include/linux/genhd.h:253
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff81291e5d)
Location: include/linux/genhd.h:247
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff81436546)
Location: include/linux/genhd.h:247
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff81437685)
Location: include/linux/genhd.h:247
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff812b4bdd)
Location: include/linux/genhd.h:251
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff814622d6)
Location: include/linux/genhd.h:251
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff81463465)
Location: include/linux/genhd.h:251
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff812dcd6b)
Location: include/linux/genhd.h:252
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff81495b11)
Location: include/linux/genhd.h:252
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff81496d85)
Location: include/linux/genhd.h:252
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff812f21cb)
Location: include/linux/genhd.h:254
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff814af9c1)
Location: include/linux/genhd.h:254
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff814b0ca5)
Location: include/linux/genhd.h:254
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff81313c5c)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff814ddd73)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff814df0d5)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff81326b6c)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff814f71d3)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff814f8505)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff813606ee)
Location: include/linux/genhd.h:257
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/genhd.c (ffffffff81558d85)
Location: include/linux/genhd.h:257
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:register_disk
  - block/genhd.c:disk_part_iter_next
```
```
In block/partitions/core.c (ffffffff8155daf2)
Location: include/linux/genhd.h:257
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/block_dev.c (ffff8000103e19fc)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffff8000105f80a4)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffff8000105f9888)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (c05b8c50)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (c07a34f8)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (c07a58cc)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (c0000000004e5780)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (c0000000007901fc)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (c000000000792188)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffe000297f3a)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffe000434f58)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffe000435f62)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff8131f14c)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff814ef7b3)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff814f0ae5)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff8130fcec)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff814dfcf3)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff814e1025)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff8131cc1c)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff814eb843)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff814ecb75)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
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
In fs/block_dev.c (ffffffff8132de22)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
```
In block/ioctl.c (ffffffff81504853)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (ffffffff81505bdf)
Location: include/linux/genhd.h:261
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdget_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:disk_part_iter_next
```
</details>
</li>
</ul>

## Differences
