# Function: <code>req_get_ioprio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/virtio_blk.c (0)
Location: include/linux/blkdev.h:202
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/virtio_blk.c (0)
Location: include/linux/blkdev.h:215
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:255
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:258
Inline: True
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:276
Inline: True
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:307
Inline: True
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:276
Inline: True
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:274
Inline: True
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:281
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8185dd9a)
Location: include/linux/blkdev.h:283
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8186ce0a)
Location: include/linux/blkdev.h:279
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8184f9cc)
Location: include/linux/blkdev.h:280
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In block/mq-deadline.c (ffffffff8160136e)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
  - block/mq-deadline.c:dd_request_merged
```
```
In drivers/ata/libata-scsi.c (ffffffff818dd144)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In block/mq-deadline.c (ffffffff816b3be2)
Location: include/linux/blk-mq.h:208
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
  - block/mq-deadline.c:dd_request_merged
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2dc35)
Location: include/linux/blk-mq.h:208
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In block/mq-deadline.c (ffffffff817739ae)
Location: include/linux/blk-mq.h:216
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
  - block/mq-deadline.c:dd_request_merged
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb1595)
Location: include/linux/blk-mq.h:216
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In block/mq-deadline.c (ffffffff817b285e)
Location: include/linux/blk-mq.h:207
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
  - block/mq-deadline.c:dd_request_merged
```
```
In drivers/block/virtio_blk.c (ffffffff81b7ea5e)
Location: include/linux/blk-mq.h:207
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81be7ae9)
Location: include/linux/blk-mq.h:207
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff81c07695)
Location: include/linux/blk-mq.h:207
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In block/mq-deadline.c (ffffffff817f669e)
Location: include/linux/blk-mq.h:201
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
  - block/mq-deadline.c:dd_request_merged
```
```
In drivers/block/virtio_blk.c (ffffffff81bd311e)
Location: include/linux/blk-mq.h:201
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81c3ce65)
Location: include/linux/blk-mq.h:201
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5c775)
Location: include/linux/blk-mq.h:201
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:281
Inline: True
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
In drivers/ata/libata-scsi.c (c0a72f90)
Location: include/linux/blkdev.h:281
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:281
Inline: True
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:281
Inline: True
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:281
Inline: True
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:281
Inline: True
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:281
Inline: True
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
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:281
Inline: True
```
</details>
</li>
</ul>

## Differences
