# Function: <code>disk_zone_no</code>

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
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81735abd)
Location: include/linux/blkdev.h:667
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/mq-deadline.c (ffffffff81773bac)
Location: include/linux/blkdev.h:667
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff81778326)
Location: include/linux/blkdev.h:667
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b971dd)
Location: include/linux/blkdev.h:667
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/md/dm-zone.c (ffffffff81d0a371)
Location: include/linux/blkdev.h:667
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
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
In block/blk-core.c (ffffffff81771fed)
Location: include/linux/blkdev.h:651
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/mq-deadline.c (ffffffff817b3f2b)
Location: include/linux/blkdev.h:651
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff817b7bd0)
Location: include/linux/blkdev.h:651
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bed7ae)
Location: include/linux/blkdev.h:651
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/md/dm-zone.c (ffffffff81d734ab)
Location: include/linux/blkdev.h:651
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
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
In block/blk-core.c (ffffffff817b3229)
Location: include/linux/blkdev.h:623
Inline: True
Inline callers:
  - block/blk-core.c:blk_check_zone_append
```
```
In block/mq-deadline.c (ffffffff817f7abb)
Location: include/linux/blkdev.h:623
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff817fc916)
Location: include/linux/blkdev.h:623
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
  - block/blk-zoned.c:blk_req_zone_write_trylock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff821fb214)
Location: include/linux/blkdev.h:623
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
In drivers/md/dm-zone.c (ffffffff81e2a582)
Location: include/linux/blkdev.h:623
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
