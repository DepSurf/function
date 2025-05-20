# Function: <code>blk_rq_zone_no</code>

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
Location: include/linux/blkdev.h:1073
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff814b7ff6)
Location: include/linux/blkdev.h:1073
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
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
Location: include/linux/blkdev.h:918
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff814cbae6)
Location: include/linux/blkdev.h:918
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
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
Location: include/linux/blkdev.h:935
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff814fa786)
Location: include/linux/blkdev.h:935
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
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
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff815186e6)
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
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
In block/mq-deadline.c (ffffffff815758d8)
Location: include/linux/blkdev.h:980
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
```
```
In block/blk-zoned.c (ffffffff81578ae0)
Location: include/linux/blkdev.h:980
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81848b35)
Location: include/linux/blkdev.h:980
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In block/mq-deadline.c (ffffffff815926d2)
Location: include/linux/blkdev.h:1028
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
```
```
In block/blk-zoned.c (ffffffff8159567f)
Location: include/linux/blkdev.h:1028
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81858ffc)
Location: include/linux/blkdev.h:1028
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In block/mq-deadline.c (ffffffff815994f4)
Location: include/linux/blkdev.h:1011
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
```
```
In block/blk-zoned.c (ffffffff8159c2cf)
Location: include/linux/blkdev.h:1011
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183bce2)
Location: include/linux/blkdev.h:1011
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In block/mq-deadline.c (ffffffff81601805)
Location: include/linux/blkdev.h:985
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff81604aa6)
Location: include/linux/blkdev.h:985
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8617)
Location: include/linux/blkdev.h:985
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In block/mq-deadline.c (ffffffff816b410f)
Location: include/linux/blk-mq.h:1122
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff816b8266)
Location: include/linux/blk-mq.h:1122
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a15677)
Location: include/linux/blk-mq.h:1122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In block/mq-deadline.c (ffffffff81773ba8)
Location: include/linux/blk-mq.h:1153
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff8177871b)
Location: include/linux/blk-mq.h:1153
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b960ab)
Location: include/linux/blk-mq.h:1153
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In block/mq-deadline.c (ffffffff817b315a)
Location: include/linux/blk-mq.h:1153
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff817b82fb)
Location: include/linux/blk-mq.h:1153
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bec8a9)
Location: include/linux/blk-mq.h:1153
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In block/mq-deadline.c (ffffffff817f6cec)
Location: include/linux/blk-mq.h:1150
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff817fcdbf)
Location: include/linux/blk-mq.h:1150
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c41f6d)
Location: include/linux/blk-mq.h:1150
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
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
In block/mq-deadline.c (ffff800010619584)
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffff800010620088)
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
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
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (c07c763c)
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
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
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (c0000000007bf768)
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
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
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffe000452776)
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
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
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff81510cc6)
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
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
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff81500fe6)
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
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
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff8150cd56)
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
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
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff81526436)
Location: include/linux/blkdev.h:958
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
</details>
</li>
</ul>

## Differences
