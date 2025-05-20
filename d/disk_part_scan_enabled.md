# Function: <code>disk_part_scan_enabled</code>

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
In fs/block_dev.c (ffffffff812480db)
Location: include/linux/genhd.h:260
Inline: True
Inline callers:
  - fs/block_dev.c:flush_disk
```
```
In block/ioctl.c (ffffffff813c88a3)
Location: include/linux/genhd.h:260
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff813cb309)
Location: include/linux/genhd.h:260
Inline: True
Inline callers:
  - block/genhd.c:add_disk
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
In fs/block_dev.c (ffffffff812708b6)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - fs/block_dev.c:flush_disk
```
```
In block/ioctl.c (ffffffff8140cb03)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff8140f5c3)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
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
In fs/block_dev.c (ffffffff81284236)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:flush_disk
```
```
In block/ioctl.c (ffffffff81427de3)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff8142a960)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
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
In fs/block_dev.c (ffffffff812918ec)
Location: include/linux/genhd.h:229
Inline: True
Inline callers:
  - fs/block_dev.c:flush_disk
```
```
In block/ioctl.c (ffffffff8143613b)
Location: include/linux/genhd.h:229
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff81438bc2)
Location: include/linux/genhd.h:229
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
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
In fs/block_dev.c (ffffffff812b4646)
Location: include/linux/genhd.h:232
Inline: True
Inline callers:
  - fs/block_dev.c:flush_disk
```
```
In block/ioctl.c (ffffffff81461e63)
Location: include/linux/genhd.h:232
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff81464b54)
Location: include/linux/genhd.h:232
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
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
In fs/block_dev.c (ffffffff812dbc6a)
Location: include/linux/genhd.h:233
Inline: True
Inline callers:
  - fs/block_dev.c:flush_disk
```
```
In block/ioctl.c (ffffffff81495783)
Location: include/linux/genhd.h:233
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff81498376)
Location: include/linux/genhd.h:233
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In fs/block_dev.c (ffffffff812f135a)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - fs/block_dev.c:flush_disk
```
```
In block/ioctl.c (ffffffff814af633)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814b24b4)
Location: include/linux/genhd.h:235
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In fs/block_dev.c (ffffffff8131320a)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:flush_disk
```
```
In block/ioctl.c (ffffffff814dd9e4)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814e0a19)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In fs/block_dev.c (ffffffff81327465)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff814f6e44)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814f9ca1)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff81557ef4)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff8155a2e9)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - block/genhd.c:register_disk
```
```
In block/partitions/core.c (ffffffff8155dc35)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:blk_drop_partitions
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
Location: include/linux/genhd.h:204
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff8157477a)
Location: include/linux/genhd.h:204
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff815760c8)
Location: include/linux/genhd.h:204
Inline: True
Inline callers:
  - block/genhd.c:register_disk
```
```
In block/partitions/core.c (ffffffff81579a4e)
Location: include/linux/genhd.h:204
Inline: True
Inline callers:
  - block/partitions/core.c:blk_add_partitions
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
Location: include/linux/genhd.h:194
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff8157c7fd)
Location: include/linux/genhd.h:194
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff8157df22)
Location: include/linux/genhd.h:194
Inline: True
Inline callers:
  - block/genhd.c:register_disk
```
```
In block/partitions/core.c (ffffffff81581732)
Location: include/linux/genhd.h:194
Inline: True
Inline callers:
  - block/partitions/core.c:blk_add_partitions
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
Location: include/linux/genhd.h:194
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/genhd.c (ffffffff815e3cfa)
Location: include/linux/genhd.h:194
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
```
```
In block/partitions/core.c (ffffffff815e6af2)
Location: include/linux/genhd.h:194
Inline: True
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
In fs/block_dev.c (ffff8000103e23f8)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffff8000105f767c)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffff8000105fb790)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (c07a2d88)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (c07a677c)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (c00000000078fce0)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (c0000000007949e0)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffe000434bb0)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffe000437856)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In fs/block_dev.c (ffffffff8131fa45)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff814ef424)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814f2281)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In fs/block_dev.c (ffffffff813105e5)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff814df964)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814e27b1)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In fs/block_dev.c (ffffffff8131d515)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff814eb4b4)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff814ee311)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In fs/block_dev.c (ffffffff8132f215)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In block/ioctl.c (ffffffff815044c4)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/ioctl.c:__blkdev_reread_part
```
```
In block/genhd.c (ffffffff815073a1)
Location: include/linux/genhd.h:242
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
```
</details>
</li>
</ul>

## Differences
