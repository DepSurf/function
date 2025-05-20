# Function: <code>disk_zone_is_seq</code>

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
In block/blk-core.c (ffffffff81735a9b)
Location: include/linux/blkdev.h:674
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-zoned.c (ffffffff81777d24)
Location: include/linux/blkdev.h:674
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b971b4)
Location: include/linux/blkdev.h:674
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/md/dm-zone.c (ffffffff81d0a0d3)
Location: include/linux/blkdev.h:674
Inline: True
Inline callers:
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
In block/blk-core.c (ffffffff81771fcb)
Location: include/linux/blkdev.h:658
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/mq-deadline.c (ffffffff817b3f0d)
Location: include/linux/blkdev.h:658
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff817b7897)
Location: include/linux/blkdev.h:658
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bed6d7)
Location: include/linux/blkdev.h:658
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/md/dm-zone.c (ffffffff81d7320f)
Location: include/linux/blkdev.h:658
Inline: True
Inline callers:
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
In block/blk-core.c (ffffffff817b31fb)
Location: include/linux/blkdev.h:630
Inline: True
Inline callers:
  - block/blk-core.c:blk_check_zone_append
```
```
In block/mq-deadline.c (ffffffff817f7a8f)
Location: include/linux/blkdev.h:630
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff817fc107)
Location: include/linux/blkdev.h:630
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c42df3)
Location: include/linux/blkdev.h:630
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/md/dm-zone.c (ffffffff81e2a30a)
Location: include/linux/blkdev.h:630
Inline: True
Inline callers:
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
