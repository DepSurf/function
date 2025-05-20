# Function: <code>bdev_zone_sectors</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff8142d187)
Location: include/linux/blkdev.h:1552
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
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
In block/partition-generic.c (ffffffff8143a4fd)
Location: include/linux/blkdev.h:1577
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffffffff81750704)
Location: include/linux/blkdev.h:1577
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/partition-generic.c (ffffffff81466520)
Location: include/linux/blkdev.h:1592
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffffffff817c28e4)
Location: include/linux/blkdev.h:1592
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/partition-generic.c (ffffffff81499e1f)
Location: include/linux/blkdev.h:1633
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffffffff8180b014)
Location: include/linux/blkdev.h:1633
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff814aff09)
Location: include/linux/blkdev.h:1412
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814b412f)
Location: include/linux/blkdev.h:1412
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffffffff81837011)
Location: include/linux/blkdev.h:1412
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff814de55e)
Location: include/linux/blkdev.h:1426
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814e2605)
Location: include/linux/blkdev.h:1426
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffffffff81879c12)
Location: include/linux/blkdev.h:1426
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff814f799d)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814fb9c5)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffffffff818aba02)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff815584cd)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/md/dm-table.c (ffffffff8197bd24)
Location: include/linux/blkdev.h:1487
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff815748c1)
Location: include/linux/blkdev.h:1587
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81980641)
Location: include/linux/blkdev.h:1587
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff8157c944)
Location: include/linux/blkdev.h:1584
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/md/dm-table.c (ffffffff8196486d)
Location: include/linux/blkdev.h:1584
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff815e1ae4)
Location: include/linux/blkdev.h:1575
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81a0c864)
Location: include/linux/blkdev.h:1575
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff8169071e)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81b749dd)
Location: include/linux/blkdev.h:1341
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/blk-core.c (ffffffff81735a87)
Location: include/linux/blkdev.h:1303
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/ioctl.c (ffffffff8174f2f7)
Location: include/linux/blkdev.h:1303
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff817783e0)
Location: include/linux/blkdev.h:1303
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:bdev_nr_zones
```
```
In drivers/md/dm-zone.c (ffffffff81d0a309)
Location: include/linux/blkdev.h:1303
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
```
```
In drivers/md/dm-table.c (ffffffff81d1155b)
Location: include/linux/blkdev.h:1303
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/blk-core.c (ffffffff81771fba)
Location: include/linux/blkdev.h:1288
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/ioctl.c (ffffffff8178b919)
Location: include/linux/blkdev.h:1288
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff817b7c8d)
Location: include/linux/blkdev.h:1288
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:bdev_nr_zones
```
```
In drivers/md/dm-zone.c (ffffffff81d73449)
Location: include/linux/blkdev.h:1288
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
```
```
In drivers/md/dm-table.c (ffffffff81d7a9c0)
Location: include/linux/blkdev.h:1288
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/blk-core.c (ffffffff817b31d7)
Location: include/linux/blkdev.h:1268
Inline: True
Inline callers:
  - block/blk-core.c:blk_check_zone_append
```
```
In block/ioctl.c (ffffffff817ce07a)
Location: include/linux/blkdev.h:1268
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff817fcbc6)
Location: include/linux/blkdev.h:1268
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:bdev_nr_zones
```
```
In drivers/md/dm-zone.c (ffffffff81e2a669)
Location: include/linux/blkdev.h:1268
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio_end
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
```
```
In drivers/md/dm-table.c (ffffffff8220b3b1)
Location: include/linux/blkdev.h:1268
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffff8000105f8f3c)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffff8000105fd990)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffff800010b0230c)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (c07a3cbc)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (c07a8868)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (c0be1734)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (c000000000790c78)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (c0000000007973b0)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (c000000000bf11dc)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffe00043580e)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffe00043949a)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffffffe0006f1bf0)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff814eff7d)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814f3fa5)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffffffff81851882)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff814e04bd)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814e44b5)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffffffff81818e92)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff814ec00d)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814f0035)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffffffff818a0eb2)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
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
In block/ioctl.c (ffffffff8150501d)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff815090c5)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In drivers/md/dm-table.c (ffffffff818bd0f2)
Location: include/linux/blkdev.h:1453
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
</details>
</li>
</ul>

## Differences
