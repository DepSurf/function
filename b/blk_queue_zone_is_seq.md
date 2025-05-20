# Function: <code>blk_queue_zone_is_seq</code>

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
Location: include/linux/blkdev.h:816
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
Location: include/linux/blkdev.h:696
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
Location: include/linux/blkdev.h:708
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
Location: include/linux/blkdev.h:725
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
In block/blk-core.c (ffffffff81544a77)
Location: include/linux/blkdev.h:726
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-zoned.c (ffffffff81578999)
Location: include/linux/blkdev.h:726
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff8184952f)
Location: include/linux/blkdev.h:726
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
In block/blk-core.c (ffffffff81560310)
Location: include/linux/blkdev.h:745
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-zoned.c (ffffffff815951df)
Location: include/linux/blkdev.h:745
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff818597ea)
Location: include/linux/blkdev.h:745
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
In block/blk-core.c (ffffffff815683dd)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-zoned.c (ffffffff8159bf92)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c4d9)
Location: include/linux/blkdev.h:747
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
In block/blk-core.c (ffffffff815cc9df)
Location: include/linux/blkdev.h:713
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-zoned.c (ffffffff8160440c)
Location: include/linux/blkdev.h:713
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8e0e)
Location: include/linux/blkdev.h:713
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/md/dm-zone.c (ffffffff81a05eb0)
Location: include/linux/blkdev.h:713
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
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
In block/blk-core.c (ffffffff816795dd)
Location: include/linux/blkdev.h:685
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-zoned.c (ffffffff816b7b0f)
Location: include/linux/blkdev.h:685
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a163cd)
Location: include/linux/blkdev.h:685
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/md/dm-zone.c (ffffffff81b6dbf5)
Location: include/linux/blkdev.h:685
Inline: True
Inline callers:
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff80001061f73c)
Location: include/linux/blkdev.h:725
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
Location: include/linux/blkdev.h:725
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
Location: include/linux/blkdev.h:725
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
Location: include/linux/blkdev.h:725
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
Location: include/linux/blkdev.h:725
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
Location: include/linux/blkdev.h:725
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
Location: include/linux/blkdev.h:725
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
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
</details>
</li>
</ul>

## Differences
