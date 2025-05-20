# Function: <code>disk_devt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: include/linux/genhd.h:266
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:266
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:266
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/genhd.h:266
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/genhd.h:266
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/genhd.h:266
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/genhd.h:266
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/genhd.h:266
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/genhd.h:266
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: include/linux/genhd.h:250
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:250
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:250
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/genhd.h:250
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/genhd.h:250
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/genhd.h:250
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/genhd.h:250
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/genhd.h:250
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/genhd.h:250
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/genhd.h:250
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: include/linux/genhd.h:241
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:241
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:241
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/genhd.h:241
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/genhd.h:241
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/genhd.h:241
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/genhd.h:241
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/genhd.h:241
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/genhd.h:241
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/genhd.h:241
Inline: True
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
In kernel/trace/blktrace.c (0)
Location: include/linux/genhd.h:235
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:235
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:235
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/genhd.h:235
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/genhd.h:235
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/genhd.h:235
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/genhd.h:235
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/genhd.h:235
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/genhd.h:235
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/genhd.h:235
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810e54a3)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff81183393)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff8122462c)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/ext4/page-io.c (ffffffff8134263c)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
```
```
In block/blk-core.c (ffffffff81450441)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff81465124)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
```
In drivers/char/random.c (ffffffff8160da9f)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffffffff816c20f9)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/genhd.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff817bfe58)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffffffff817c5c09)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff817c680c)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff817cd22f)
Location: include/linux/genhd.h:238
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810ef4e7)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff811924e4)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff81246b32)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff8147e82b)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff81498a75)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (ffffffff8164759c)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffffffff816fe751)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (ffffffff817041cf)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (ffffffff81809190)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffffffff8180e96c)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff8180f18c)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff81815f10)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff810fab77)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff8119fd94)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff8125af6b)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff8149be7b)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff814b2bc5)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (ffffffff81665a3c)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffffffff81721322)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (ffffffff8172676f)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (ffffffff818352e0)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffffffff8183a92c)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff8183b16c)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff81841d80)
Location: include/linux/genhd.h:241
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In kernel/power/swap.c (ffffffff8110321d)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff811adae4)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff81275f77)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff814c9f85)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff814e1087)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (ffffffff8169bdf6)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffffffff8175c9ee)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (ffffffff81761ea1)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (ffffffff81877ca0)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffffffff8187d4bc)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff8187e13c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff81884bd5)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In kernel/power/swap.c (ffffffff8110f66d)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff811b9374)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff81285a52)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff814e3165)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff814fa4b7)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (ffffffff816beb26)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffffffff817808be)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (ffffffff81785e91)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (ffffffff818a9ac0)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffffffff818af29c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff818b02cc)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff818b69a2)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff8111a8bf)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff811d1904)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff812b7e1e)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff81541bca)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff8155b5b6)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (ffffffff81772ac6)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffffffff818469be)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (ffffffff8184a6a1)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (ffffffff81979d20)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffffffff8197fbbc)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff8198043c)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff81987262)
Location: include/linux/genhd.h:244
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff81bdffb3)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff811cf08b)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff812c34ce)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff8155e6ba)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff81576176)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - block/genhd.c:register_disk
```
```
In drivers/char/random.c (ffffffff8178dadb)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sr.c (ffffffff8185aba1)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (ffffffff8197e630)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
```
```
In drivers/md/dm-stripe.c (ffffffff81983fac)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff81984a5c)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff8198b246)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff81bd1fcc)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff811d08fb)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff81bda603)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff81566f0a)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff8157df82)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - block/genhd.c:register_disk
```
```
In drivers/char/random.c (ffffffff8177143b)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sr.c (ffffffff8183db91)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/md.c (ffffffff8194bb0a)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81962480)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
```
```
In drivers/md/dm-stripe.c (ffffffff819683aa)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff8196898c)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff8196f936)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff81caade9)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff811fd22b)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff81cbe8ba)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff815cb48a)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff815e3d1b)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
```
```
In drivers/char/random.c (ffffffff817f6fee)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sr.c (ffffffff818ca651)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/md.c (ffffffff819f0d0a)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81a09634)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
```
```
In drivers/md/dm-stripe.c (ffffffff81a107ba)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff81a1180e)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff81a18276)
Location: include/linux/genhd.h:200
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff81e5b24d)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff812372da)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff81e70938)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff8167734d)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff8169341e)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - block/genhd.c:disk_scan_partitions
```
```
In drivers/char/random.c (ffffffff81934b06)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sr.c (ffffffff81a1761f)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_free_disk
```
```
In drivers/md/md.c (ffffffff81b5a167)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81b716c0)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-stripe.c (ffffffff81b78bca)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff81b79f75)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff81b80fa1)
Location: include/linux/blkdev.h:210
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff811888c6)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff8128406a)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff813f6f98)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff817334ea)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff817520cc)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - block/genhd.c:disk_scan_partitions
```
```
In drivers/char/random.c (ffffffff81a946b6)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sr.c (ffffffff81b97e3f)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_free_disk
```
```
In drivers/md/md.c (ffffffff81cf28e7)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81d0e510)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-stripe.c (ffffffff81d1625a)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff81d17455)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff81d1f30e)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff81199a83)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff812a0d1a)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff8142a0c1)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
  - mm/page_io.c:__end_swap_bio_write
```
```
In block/blk-core.c (ffffffff8176f90a)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff8178c9d5)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - block/genhd.c:disk_scan_partitions
```
```
In drivers/char/random.c (ffffffff81adfed6)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sr.c (ffffffff81bee3bf)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_free_disk
```
```
In drivers/md/md.c (ffffffff81d5a7a7)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81d77b10)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-table.c (ffffffff821487ae)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff81d7ede7)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff81d806f5)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff81d884f0)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff811a8ae3)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff812bc443)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff814634e6)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
  - mm/page_io.c:__end_swap_bio_write
```
```
In block/blk-core.c (ffffffff817b1b77)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff817cf1a5)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/genhd.c:disk_scan_partitions
```
```
In drivers/char/random.c (ffffffff81b332f6)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sr.c (ffffffff81c43acf)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_free_disk
```
```
In drivers/md/md.c (ffffffff81e11bd7)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81e2ed40)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-table.c (ffffffff8222b16e)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff81e36407)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff81e37d55)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff81e3fc00)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/trace/blktrace.c (ffff800010237be8)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffff800010320180)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffff8000105e2270)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffff8000105fc080)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (ffff8000108af93c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffff800010987010)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (ffff80001098ce40)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (ffff800010afe0a8)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffff800010b06668)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffff800010b073a0)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffff800010b0e9e0)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (c03c0b94)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (c04736b8)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (c05389e8)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (c078d2d0)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (c07a70d0)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (c09aaf3c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (c0a5931c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (c0a5e718)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (c0bdf778)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (c0be4934)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (c0be5e70)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (c0becdd0)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/trace/blktrace.c (c0000000002c3b44)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (c0000000003f5054)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (c000000000772dc0)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (c0000000007954f4)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (c00000000094797c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (c000000000a46834)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (c000000000a4d354)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (c000000000beef18)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (c000000000bf6704)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (c000000000bf82bc)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (c000000000c01af4)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/trace/blktrace.c (ffffffe00018e6ca)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffe00022186c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffe000422d36)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffe00043804e)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (ffffffe00056322e)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffffffe0005eb528)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (ffffffe0005f0d34)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (ffffffe0006eff1c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffffffe0006f4d8e)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f5c9c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffe0006fbccc)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff81107b3d)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff811b1994)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff8127e0a2)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff814db745)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff814f2a97)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (ffffffff81684596)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffffffff81734fae)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (ffffffff8173a581)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/nvme/host/multipath.c (ffffffff81749dd8)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In drivers/md/dm.c (ffffffff8184f940)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffffffff8185511c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff8185614c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff8185c822)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff810f8b2d)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff811a4934)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff8126fed2)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff814cc0f5)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff814e2fc7)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (ffffffff81662216)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffffffff81716c4e)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (ffffffff8171c221)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/nvme/host/multipath.c (ffffffff8172b9b2)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In drivers/md/dm.c (ffffffff81816f50)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffffffff8181c72c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff8181d75c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff81823df2)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff81105b3d)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff811af764)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff8127be42)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff814d77d5)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff814eeb27)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (ffffffff816b2966)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffffffff8177573e)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (ffffffff8177ad11)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (ffffffff8189ef70)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffffffff818a474c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff818a577c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff818abe52)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
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
In kernel/power/swap.c (ffffffff81110f1d)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (ffffffff811bd7e3)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In mm/page_io.c (ffffffff8128ba22)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In block/blk-core.c (ffffffff814f03e5)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/genhd.c (ffffffff81507bd1)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
```
```
In drivers/char/random.c (ffffffff816ccea6)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_disk_randomness
```
```
In drivers/scsi/sd.c (ffffffff8178f51e)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
```
```
In drivers/scsi/sr.c (ffffffff817950b1)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/md/dm.c (ffffffff818bb65b)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stripe.c (ffffffff818c098c)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-ioctl.c (ffffffff818c19bc)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:list_devices
```
```
In drivers/md/dm-rq.c (ffffffff818c8092)
Location: include/linux/genhd.h:248
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
</details>
</li>
</ul>

## Differences
