# Function: <code>blk_queue_zone_no</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff814ad9f7)
Location: include/linux/blkdev.h:808
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff814b7ff6)
Location: include/linux/blkdev.h:808
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/mq-deadline.c (ffffffff814c8175)
Location: include/linux/blkdev.h:688
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff814cbae6)
Location: include/linux/blkdev.h:688
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/mq-deadline.c (ffffffff814f6a17)
Location: include/linux/blkdev.h:700
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff814fa786)
Location: include/linux/blkdev.h:700
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/mq-deadline.c (ffffffff815148c7)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff815186e6)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-core.c (ffffffff81542f90)
Location: include/linux/blkdev.h:718
Inline: True
Direct callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/mq-deadline.c (ffffffff815756c0)
Location: include/linux/blkdev.h:718
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_fifo_request
```
```
In block/blk-zoned.c (ffffffff81578ae0)
Location: include/linux/blkdev.h:718
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
Direct callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81849549)
Location: include/linux/blkdev.h:718
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81542f90-ffffffff81542faa: blk_queue_zone_no.isra.0 (STB_LOCAL)
ffffffff815756c0-ffffffff815756da: blk_queue_zone_no.isra.0 (STB_LOCAL)
ffffffff81578950-ffffffff8157895f: blk_queue_zone_no.part.0.isra.0 (STB_LOCAL)
ffffffff81848ae0-ffffffff81848aef: blk_queue_zone_no.part.0.isra.0 (STB_LOCAL)
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
In block/blk-core.c (ffffffff81560315)
Location: include/linux/blkdev.h:737
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/mq-deadline.c (ffffffff815926e5)
Location: include/linux/blkdev.h:737
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
```
```
In block/blk-zoned.c (ffffffff8159567f)
Location: include/linux/blkdev.h:737
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81859804)
Location: include/linux/blkdev.h:737
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
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
In block/blk-core.c (ffffffff815683e9)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/mq-deadline.c (ffffffff81599507)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
```
```
In block/blk-zoned.c (ffffffff8159c2d9)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c4f8)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
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
In block/blk-core.c (ffffffff815cc9eb)
Location: include/linux/blkdev.h:705
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/mq-deadline.c (ffffffff81601805)
Location: include/linux/blkdev.h:705
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff816045ce)
Location: include/linux/blkdev.h:705
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8e2f)
Location: include/linux/blkdev.h:705
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/md/dm-zone.c (ffffffff81a061d4)
Location: include/linux/blkdev.h:705
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio_end
  - drivers/md/dm-zone.c:dm_zone_map_bio_end
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
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
In block/blk-core.c (ffffffff816795e9)
Location: include/linux/blkdev.h:677
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/mq-deadline.c (ffffffff816b410f)
Location: include/linux/blkdev.h:677
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff816b7d20)
Location: include/linux/blkdev.h:677
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a163f2)
Location: include/linux/blkdev.h:677
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/md/dm-zone.c (ffffffff81b6de42)
Location: include/linux/blkdev.h:677
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
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
In block/mq-deadline.c (ffff800010619584)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffff800010620088)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/mq-deadline.c (c07c4078)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (c07c7640)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/mq-deadline.c (c0000000007b8d50)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (c0000000007bf76c)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/mq-deadline.c (ffffffe00044f256)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffe000452778)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/mq-deadline.c (ffffffff8150cea7)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff81510cc6)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/mq-deadline.c (ffffffff814fd2d7)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff81500fe6)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/mq-deadline.c (ffffffff81508f37)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff8150cd56)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/mq-deadline.c (ffffffff815226d7)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff81526436)
Location: include/linux/blkdev.h:717
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
</details>
</li>
</ul>

## Differences
