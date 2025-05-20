# Function: <code>blk_queue_zone_sectors</code>

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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff8142d187)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffff81448c46)
Location: include/linux/blkdev.h:742
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
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
Location: include/linux/blkdev.h:785
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffff814571c1)
Location: include/linux/blkdev.h:785
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/dm-table.c (ffffffff817500f1)
Location: include/linux/blkdev.h:785
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
Location: include/linux/blkdev.h:805
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffff81482ecb)
Location: include/linux/blkdev.h:805
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/dm-table.c (ffffffff817c22d1)
Location: include/linux/blkdev.h:805
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
Location: include/linux/blkdev.h:798
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffff814b7e51)
Location: include/linux/blkdev.h:798
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/dm-table.c (ffffffff8180abf1)
Location: include/linux/blkdev.h:798
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/ioctl.c (ffffffff814aff1e)
Location: include/linux/blkdev.h:677
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814b412f)
Location: include/linux/blkdev.h:677
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffff814cbb5c)
Location: include/linux/blkdev.h:677
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blk_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-table.c (ffffffff81836be1)
Location: include/linux/blkdev.h:677
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/ioctl.c (ffffffff814de573)
Location: include/linux/blkdev.h:689
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814e2605)
Location: include/linux/blkdev.h:689
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffff814fa3ff)
Location: include/linux/blkdev.h:689
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blk_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-table.c (ffffffff818797e2)
Location: include/linux/blkdev.h:689
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/ioctl.c (ffffffff814f79b2)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814fb9c5)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffff8151835f)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blk_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-table.c (ffffffff818ab5e2)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/blk-core.c (ffffffff81544a5f)
Location: include/linux/blkdev.h:707
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/ioctl.c (ffffffff815584e6)
Location: include/linux/blkdev.h:707
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff815787a4)
Location: include/linux/blkdev.h:707
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm.c (ffffffff81979f2a)
Location: include/linux/blkdev.h:707
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff8197b7a2)
Location: include/linux/blkdev.h:707
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/blk-core.c (ffffffff815602f8)
Location: include/linux/blkdev.h:726
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/ioctl.c (ffffffff815748d4)
Location: include/linux/blkdev.h:726
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff815952a1)
Location: include/linux/blkdev.h:726
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm.c (ffffffff8197ed43)
Location: include/linux/blkdev.h:726
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff8197fe88)
Location: include/linux/blkdev.h:726
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
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
In block/blk-core.c (ffffffff815683c6)
Location: include/linux/blkdev.h:728
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/ioctl.c (ffffffff8157c957)
Location: include/linux/blkdev.h:728
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff8159c051)
Location: include/linux/blkdev.h:728
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm.c (ffffffff81962bad)
Location: include/linux/blkdev.h:728
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81963fe8)
Location: include/linux/blkdev.h:728
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
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
In block/blk-core.c (ffffffff815cc9c8)
Location: include/linux/blkdev.h:694
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/ioctl.c (ffffffff815e1af7)
Location: include/linux/blkdev.h:694
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff81604681)
Location: include/linux/blkdev.h:694
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-zone.c (ffffffff81a0623c)
Location: include/linux/blkdev.h:694
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio_end
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
```
```
In drivers/md/dm-table.c (ffffffff81a0bf98)
Location: include/linux/blkdev.h:694
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
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
In block/blk-core.c (ffffffff816795c6)
Location: include/linux/blkdev.h:666
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/ioctl.c (ffffffff8169072c)
Location: include/linux/blkdev.h:666
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/blk-zoned.c (ffffffff816b7dd0)
Location: include/linux/blkdev.h:666
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-zone.c (ffffffff81b6deec)
Location: include/linux/blkdev.h:666
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
```
```
In drivers/md/dm-table.c (ffffffff81b74653)
Location: include/linux/blkdev.h:666
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_matches_zone_sectors
  - drivers/md/dm-table.c:device_area_is_invalid
```
</details>
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
In block/ioctl.c (ffff8000105f8f4c)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffff8000105fd990)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffff80001061fd08)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blk_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-table.c (ffff800010b01d88)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/ioctl.c (c07a3ccc)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (c07a8868)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (c07c7808)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blk_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-table.c (c0be0f4c)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/ioctl.c (c000000000790c88)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (c0000000007973b0)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (c0000000007bf2f8)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blk_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-table.c (c000000000bf0c10)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/ioctl.c (ffffffe00043581c)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffe00043949a)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffe00045249c)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blk_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-table.c (ffffffe0006f177c)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/ioctl.c (ffffffff814eff92)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814f3fa5)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffff8151093f)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blk_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-table.c (ffffffff81851462)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/ioctl.c (ffffffff814e04d2)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814e44b5)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffff81500c5f)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blk_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-table.c (ffffffff81818a72)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/ioctl.c (ffffffff814ec022)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff814f0035)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffff8150c9cf)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blk_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-table.c (ffffffff818a0a92)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
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
In block/ioctl.c (ffffffff81505032)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/partition-generic.c (ffffffff815090c5)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/blk-zoned.c (ffffffff815260af)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blk_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In drivers/md/dm-table.c (ffffffff818bccd2)
Location: include/linux/blkdev.h:706
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_matches_zone_sectors
  - drivers/md/dm-table.c:device_area_is_invalid
```
</details>
</li>
</ul>

## Differences
