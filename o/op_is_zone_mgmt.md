# Function: <code>op_is_zone_mgmt</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815787e4)
Location: include/linux/blk_types.h:451
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/scsi/sd_zbc.c (ffffffff818494d2)
Location: include/linux/blk_types.h:451
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
```
In drivers/md/dm.c (ffffffff81979548)
Location: include/linux/blk_types.h:451
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
```
```
In drivers/md/dm-linear.c (ffffffff8197ed31)
Location: include/linux/blk_types.h:451
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
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
In block/blk-zoned.c (ffffffff815952e9)
Location: include/linux/blk_types.h:515
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/scsi/sd_zbc.c (ffffffff8185978e)
Location: include/linux/blk_types.h:515
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
```
In drivers/md/dm.c (ffffffff8197d2c3)
Location: include/linux/blk_types.h:515
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
```
```
In drivers/md/dm-linear.c (ffffffff81983144)
Location: include/linux/blk_types.h:515
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
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
In block/blk-zoned.c (ffffffff8159c099)
Location: include/linux/blk_types.h:489
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c494)
Location: include/linux/blk_types.h:489
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
```
In drivers/md/dm.c (ffffffff81961397)
Location: include/linux/blk_types.h:489
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_accept_partial_bio
```
```
In drivers/md/dm-linear.c (ffffffff81967575)
Location: include/linux/blk_types.h:489
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
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
In block/blk-zoned.c (ffffffff816046d2)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8db4)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
```
In drivers/md/dm.c (ffffffff81a0afa7)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_accept_partial_bio
```
```
In drivers/md/dm-linear.c (ffffffff81a0f7e5)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
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
In block/blk-zoned.c (ffffffff816b7e81)
Location: include/linux/blk_types.h:512
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a16324)
Location: include/linux/blk_types.h:512
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
```
In drivers/md/dm.c (ffffffff81b72ade)
Location: include/linux/blk_types.h:512
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_accept_partial_bio
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
In block/blk-zoned.c (ffffffff81778491)
Location: include/linux/blk_types.h:511
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b97104)
Location: include/linux/blk_types.h:511
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
```
In drivers/md/dm.c (ffffffff81d0f879)
Location: include/linux/blk_types.h:511
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_accept_partial_bio
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
In block/blk-zoned.c (ffffffff817b7d3a)
Location: include/linux/blk_types.h:516
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bed6a4)
Location: include/linux/blk_types.h:516
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
```
In drivers/md/dm.c (ffffffff81d78c9b)
Location: include/linux/blk_types.h:516
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_accept_partial_bio
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
In block/blk-zoned.c (ffffffff817fcc5d)
Location: include/linux/blk_types.h:515
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c42da3)
Location: include/linux/blk_types.h:515
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
```
In drivers/md/dm.c (ffffffff81e2feda)
Location: include/linux/blk_types.h:515
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_accept_partial_bio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
