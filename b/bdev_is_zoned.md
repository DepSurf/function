# Function: <code>bdev_is_zoned</code>

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
In block/blk-core.c (ffffffff81414cab)
Location: include/linux/blkdev.h:1542
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/partition-generic.c (ffffffff8142d166)
Location: include/linux/blkdev.h:1542
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
In block/blk-core.c (ffffffff814248ac)
Location: include/linux/blkdev.h:1567
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/partition-generic.c (ffffffff8143a482)
Location: include/linux/blkdev.h:1567
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814664a5)
Location: include/linux/blkdev.h:1582
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81499d8a)
Location: include/linux/blkdev.h:1623
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814b409a)
Location: include/linux/blkdev.h:1402
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e2586)
Location: include/linux/blkdev.h:1416
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814fb946)
Location: include/linux/blkdev.h:1443
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0c7ff)
Location: include/linux/blkdev.h:1565
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
In mm/swapfile.c (ffffffff81382b5c)
Location: include/linux/blkdev.h:1331
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In drivers/md/dm-table.c (ffffffff81b74980)
Location: include/linux/blkdev.h:1331
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
In mm/swapfile.c (ffffffff813fcab6)
Location: include/linux/blkdev.h:1284
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In block/bio.c (ffffffff8172f451)
Location: include/linux/blkdev.h:1284
Inline: True
Inline callers:
  - block/bio.c:bio_add_zone_append_page
```
```
In block/blk-core.c (ffffffff8173581b)
Location: include/linux/blkdev.h:1284
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (ffffffff8173ef23)
Location: include/linux/blkdev.h:1284
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff81747bf7)
Location: include/linux/blkdev.h:1284
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-zoned.c (ffffffff817788fd)
Location: include/linux/blkdev.h:1284
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:bdev_nr_zones
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/md/dm-zone.c (ffffffff81d09485)
Location: include/linux/blkdev.h:1284
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:device_not_zone_append_capable
```
```
In drivers/md/dm.c (ffffffff81d0eed1)
Location: include/linux/blkdev.h:1284
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81d11525)
Location: include/linux/blkdev.h:1284
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
In mm/swapfile.c (ffffffff8142fe38)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In block/bio.c (ffffffff8176b701)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - block/bio.c:bio_add_zone_append_page
```
```
In block/blk-core.c (ffffffff81771f32)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (ffffffff8177b495)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff817842a4)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-zoned.c (ffffffff817b84c1)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones
```
```
In drivers/md/dm-zone.c (ffffffff81d72605)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:device_not_zone_append_capable
```
```
In drivers/md/dm.c (ffffffff81d780ea)
Location: include/linux/blkdev.h:1266
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81d7a9a5)
Location: include/linux/blkdev.h:1266
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
In mm/swapfile.c (ffffffff814698d0)
Location: include/linux/blkdev.h:1246
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In block/bio.c (ffffffff817adbb1)
Location: include/linux/blkdev.h:1246
Inline: True
Inline callers:
  - block/bio.c:bio_add_zone_append_page
```
```
In block/blk-core.c (ffffffff817b442e)
Location: include/linux/blkdev.h:1246
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:blk_check_zone_append
```
```
In block/blk-merge.c (ffffffff817bd884)
Location: include/linux/blkdev.h:1246
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff817c65b2)
Location: include/linux/blkdev.h:1246
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/partitions/core.c (ffffffff817d46a4)
Location: include/linux/blkdev.h:1246
Inline: True
Inline callers:
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:add_partition
```
```
In block/blk-zoned.c (ffffffff817fcfa9)
Location: include/linux/blkdev.h:1246
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:bdev_nr_zones
```
```
In drivers/md/dm-zone.c (ffffffff81e299c5)
Location: include/linux/blkdev.h:1246
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:device_not_zone_append_capable
```
```
In drivers/md/dm.c (ffffffff81e2f31a)
Location: include/linux/blkdev.h:1246
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-table.c (ffffffff81e32e25)
Location: include/linux/blkdev.h:1246
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_zoned_model
  - drivers/md/dm-table.c:device_not_zoned
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3ca6c)
Location: include/linux/blkdev.h:1246
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffff8000105fd8f8)
Location: include/linux/blkdev.h:1443
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c07a87ec)
Location: include/linux/blkdev.h:1443
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c0000000007972d4)
Location: include/linux/blkdev.h:1443
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffe0004393f0)
Location: include/linux/blkdev.h:1443
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814f3f26)
Location: include/linux/blkdev.h:1443
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e4436)
Location: include/linux/blkdev.h:1443
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814effb6)
Location: include/linux/blkdev.h:1443
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81509046)
Location: include/linux/blkdev.h:1443
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
</details>
</li>
</ul>

## Differences
