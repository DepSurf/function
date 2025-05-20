# Function: <code>blk_rq_zone_is_seq</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814b7f3e)
Location: include/linux/blkdev.h:1078
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-zoned.c (ffffffff814cba3e)
Location: include/linux/blkdev.h:923
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-zoned.c (ffffffff814fa38e)
Location: include/linux/blkdev.h:940
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-zoned.c (ffffffff8151809e)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-zoned.c (ffffffff81578999)
Location: include/linux/blkdev.h:985
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff8184952c)
Location: include/linux/blkdev.h:985
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
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
In block/blk-zoned.c (ffffffff815951df)
Location: include/linux/blkdev.h:1033
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff818597e6)
Location: include/linux/blkdev.h:1033
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
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
In block/blk-zoned.c (ffffffff8159bf92)
Location: include/linux/blkdev.h:1016
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c4d5)
Location: include/linux/blkdev.h:1016
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
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
In block/blk-zoned.c (ffffffff8160440c)
Location: include/linux/blkdev.h:990
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8e07)
Location: include/linux/blkdev.h:990
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
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
In block/blk-zoned.c (ffffffff816b7b0f)
Location: include/linux/blk-mq.h:1127
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a163c6)
Location: include/linux/blk-mq.h:1127
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
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
In block/blk-zoned.c (ffffffff81777d24)
Location: include/linux/blk-mq.h:1158
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b971a6)
Location: include/linux/blk-mq.h:1158
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
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
In block/mq-deadline.c (ffffffff817b3eff)
Location: include/linux/blk-mq.h:1158
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
Location: include/linux/blk-mq.h:1158
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bed6c2)
Location: include/linux/blk-mq.h:1158
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
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
In block/mq-deadline.c (ffffffff817f7a8b)
Location: include/linux/blk-mq.h:1155
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
In block/blk-zoned.c (ffffffff817fc0ff)
Location: include/linux/blk-mq.h:1155
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c42de1)
Location: include/linux/blk-mq.h:1155
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
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
In block/blk-zoned.c (ffff80001061f73c)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-zoned.c (c07c7248)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-zoned.c (c0000000007bf25c)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-zoned.c (ffffffe0004523ea)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-zoned.c (ffffffff8151067e)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-zoned.c (ffffffff8150099e)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-zoned.c (ffffffff8150c70e)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-zoned.c (ffffffff81525dee)
Location: include/linux/blkdev.h:963
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
</details>
</li>
</ul>

## Differences
