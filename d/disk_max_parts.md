# Function: <code>disk_max_parts</code>

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
In fs/block_dev.c (0)
Location: include/linux/genhd.h:253
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/genhd.h:253
Inline: True
```
```
In block/genhd.c (ffffffff813c9ff6)
Location: include/linux/genhd.h:253
Inline: True
Inline callers:
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partitions/check.c (ffffffff813ce2c5)
Location: include/linux/genhd.h:253
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (0)
Location: include/linux/genhd.h:237
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/genhd.h:237
Inline: True
```
```
In block/genhd.c (ffffffff8140f76d)
Location: include/linux/genhd.h:237
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
```
```
In block/partitions/check.c (ffffffff81413385)
Location: include/linux/genhd.h:237
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (0)
Location: include/linux/genhd.h:228
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/genhd.h:228
Inline: True
```
```
In block/genhd.c (ffffffff8142aafd)
Location: include/linux/genhd.h:228
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
```
```
In block/partitions/check.c (ffffffff8142e8b5)
Location: include/linux/genhd.h:228
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (0)
Location: include/linux/genhd.h:222
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/genhd.h:222
Inline: True
```
```
In block/genhd.c (ffffffff81438d1b)
Location: include/linux/genhd.h:222
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
```
```
In block/partitions/check.c (ffffffff8143bbc5)
Location: include/linux/genhd.h:222
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (0)
Location: include/linux/genhd.h:225
Inline: True
```
```
In block/ioctl.c (0)
Location: include/linux/genhd.h:225
Inline: True
```
```
In block/genhd.c (ffffffff81464ceb)
Location: include/linux/genhd.h:225
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
```
```
In block/partitions/check.c (ffffffff81467bd5)
Location: include/linux/genhd.h:225
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (ffffffff812dbc70)
Location: include/linux/genhd.h:226
Inline: True
Inline callers:
  - fs/block_dev.c:flush_disk
```
```
In block/ioctl.c (ffffffff8149578b)
Location: include/linux/genhd.h:226
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff8149862e)
Location: include/linux/genhd.h:226
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (ffffffff8149ba4c)
Location: include/linux/genhd.h:226
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (ffffffff812f1360)
Location: include/linux/genhd.h:228
Inline: True
Inline callers:
  - fs/block_dev.c:flush_disk
```
```
In block/ioctl.c (ffffffff814af63b)
Location: include/linux/genhd.h:228
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814b277e)
Location: include/linux/genhd.h:228
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (ffffffff814b5d5e)
Location: include/linux/genhd.h:228
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (ffffffff81313214)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:flush_disk
```
```
In block/ioctl.c (ffffffff814dd9f3)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814e0c13)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (ffffffff814e42ae)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (ffffffff8132746f)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff814f6e53)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814fa043)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (ffffffff814fd66e)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (ffffffff813601cf)
Location: include/linux/genhd.h:231
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff81557ef4)
Location: include/linux/genhd.h:231
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff8155af0e)
Location: include/linux/genhd.h:231
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:register_disk
```
```
In block/partitions/core.c (ffffffff8155dc35)
Location: include/linux/genhd.h:231
Inline: True
Inline callers:
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:check_partition
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
In fs/block_dev.c (ffffffff8136c834)
Location: include/linux/genhd.h:197
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff8157477a)
Location: include/linux/genhd.h:197
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff8157719e)
Location: include/linux/genhd.h:197
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:register_disk
```
```
In block/partitions/core.c (ffffffff81579a4e)
Location: include/linux/genhd.h:197
Inline: True
Inline callers:
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:check_partition
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
In fs/block_dev.c (ffffffff813740ee)
Location: include/linux/genhd.h:187
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff8157c7fd)
Location: include/linux/genhd.h:187
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff8157d768)
Location: include/linux/genhd.h:187
Inline: True
Inline callers:
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:register_disk
```
```
In block/partitions/core.c (ffffffff81581732)
Location: include/linux/genhd.h:187
Inline: True
Inline callers:
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:check_partition
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
In block/ioctl.c (ffffffff815e1c55)
Location: include/linux/genhd.h:187
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff815e2fa8)
Location: include/linux/genhd.h:187
Inline: True
Inline callers:
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:device_add_disk
```
```
In block/partitions/core.c (ffffffff815e64f5)
Location: include/linux/genhd.h:187
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:check_partition
```
</details>
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
In fs/block_dev.c (ffff8000103e23fc)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffff8000105f7680)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffff8000105fbbac)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (ffff8000105ff210)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (c05ba5c8)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (c07a2d88)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (c07a6c4c)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (c07aa4c8)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (c0000000004e8008)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (c00000000078fce0)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (c000000000794e9c)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (c000000000799298)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (ffffffe0002989b6)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffe000434bb0)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffe000437c48)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (ffffffe00043a7f8)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (ffffffff8131fa4f)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff814ef433)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814f2623)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (ffffffff814f5c4e)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (ffffffff813105ef)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff814df973)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814e2b53)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (ffffffff814e615e)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (ffffffff8131d51f)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff814eb4c3)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814ee6b3)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (ffffffff814f1cde)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
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
In fs/block_dev.c (ffffffff8132f21f)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff815044d3)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff81507753)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:disk_ext_range_show
  - block/genhd.c:__device_add_disk
```
```
In block/partitions/check.c (ffffffff8150ad3e)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
</details>
</li>
</ul>

## Differences
