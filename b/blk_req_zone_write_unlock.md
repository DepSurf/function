# Function: <code>blk_req_zone_write_unlock</code>

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
In block/blk-core.c (ffffffff814819f3)
Location: include/linux/blkdev.h:1991
Inline: True
Inline callers:
  - block/blk-core.c:__blk_put_request
```
```
In block/deadline-iosched.c (ffffffff814ad855)
Location: include/linux/blkdev.h:1991
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_completed_request
  - block/deadline-iosched.c:deadline_add_request
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
In block/mq-deadline.c (ffffffff814c7dea)
Location: include/linux/blkdev.h:1679
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
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
In block/mq-deadline.c (ffffffff814f667b)
Location: include/linux/blkdev.h:1703
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
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
In block/mq-deadline.c (ffffffff8151472d)
Location: include/linux/blkdev.h:1734
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
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
In block/mq-deadline.c (ffffffff815757dd)
Location: include/linux/blkdev.h:1797
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
```
In drivers/scsi/sd_zbc.c (ffffffff81849578)
Location: include/linux/blkdev.h:1797
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
In block/mq-deadline.c (ffffffff815925dd)
Location: include/linux/blkdev.h:1897
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
```
In drivers/scsi/sd_zbc.c (ffffffff818597ce)
Location: include/linux/blkdev.h:1897
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
In block/mq-deadline.c (ffffffff81598fcd)
Location: include/linux/blkdev.h:1893
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c521)
Location: include/linux/blkdev.h:1893
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
In block/mq-deadline.c (ffffffff816013db)
Location: include/linux/blkdev.h:1891
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_request
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8e6b)
Location: include/linux/blkdev.h:1891
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
In block/mq-deadline.c (ffffffff816b3c54)
Location: include/linux/blk-mq.h:1143
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a1638d)
Location: include/linux/blk-mq.h:1143
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
In block/mq-deadline.c (ffffffff81773a1a)
Location: include/linux/blk-mq.h:1174
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b9716d)
Location: include/linux/blk-mq.h:1174
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
In block/mq-deadline.c (ffffffff817b28ca)
Location: include/linux/blk-mq.h:1186
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bed734)
Location: include/linux/blk-mq.h:1186
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
In block/mq-deadline.c (ffffffff817f6711)
Location: include/linux/blk-mq.h:1183
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c42e62)
Location: include/linux/blk-mq.h:1183
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
In block/mq-deadline.c (ffff800010619960)
Location: include/linux/blkdev.h:1734
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
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
In block/mq-deadline.c (c07c3e30)
Location: include/linux/blkdev.h:1734
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
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
In block/mq-deadline.c (c0000000007b89a0)
Location: include/linux/blkdev.h:1734
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
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
In block/mq-deadline.c (ffffffe00044f0ea)
Location: include/linux/blkdev.h:1734
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
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
In block/mq-deadline.c (ffffffff8150cd0d)
Location: include/linux/blkdev.h:1734
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
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
In block/mq-deadline.c (ffffffff814fd13d)
Location: include/linux/blkdev.h:1734
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
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
In block/mq-deadline.c (ffffffff81508d9d)
Location: include/linux/blkdev.h:1734
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
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
In block/mq-deadline.c (ffffffff8152249d)
Location: include/linux/blkdev.h:1734
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
</ul>

## Differences
