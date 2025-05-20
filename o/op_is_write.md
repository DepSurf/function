# Function: <code>op_is_write</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff811670ef)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
```
```
In fs/mpage.c (ffffffff81275d16)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In block/bio.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In block/elevator.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In block/blk-core.c (ffffffff813fe6c6)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-map.c (ffffffff81403619)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user
```
```
In block/blk-merge.c (ffffffff8140584b)
Location: include/linux/fs.h:2499
Inline: True
```
```
In block/blk-mq.c (ffffffff81408da5)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In block/scsi_ioctl.c (ffffffff8141081d)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bounce.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In block/blk-throttle.c (ffffffff814218d3)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/deadline-iosched.c (ffffffff814225f9)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/deadline-iosched.c:deadline_merged_request
  - block/deadline-iosched.c:deadline_merged_request
  - block/deadline-iosched.c:deadline_add_request
```
```
In block/cfq-iosched.c (ffffffff8142a8f3)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
```
```
In block/bio-integrity.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In drivers/block/brd.c (ffffffff815c3150)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_make_request
```
```
In drivers/block/loop.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff815cbf67)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/nvdimm/core.c (ffffffff815eba09)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_iostat_end
  - drivers/nvdimm/core.c:__nd_iostat_start
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81614662)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In drivers/md/md.c (ffffffff816f0fed)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff817035c1)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/fs.h:2499
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff8170f94d)
Location: include/linux/fs.h:2499
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In kernel/power/swap.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In block/elevator.c (ffffffff81411121)
Location: include/linux/blk_types.h:218
Inline: True
Inline callers:
  - block/elevator.c:elv_dispatch_sort
  - block/elevator.c:elv_dispatch_sort
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In block/blk-map.c (ffffffff8141d41a)
Location: include/linux/blk_types.h:218
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (ffffffff8141fe21)
Location: include/linux/blk_types.h:218
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In block/bounce.c (ffffffff81436269)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In block/blk-throttle.c (ffffffff8143cb54)
Location: include/linux/blk_types.h:218
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/deadline-iosched.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff815f8b5e)
Location: include/linux/blk_types.h:218
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81644189)
Location: include/linux/blk_types.h:218
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In drivers/md/md.c (ffffffff8172289b)
Location: include/linux/blk_types.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff8173534c)
Location: include/linux/blk_types.h:218
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/blk_types.h:218
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81740fff)
Location: include/linux/blk_types.h:218
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_start_request
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
In kernel/power/swap.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In block/elevator.c (ffffffff8141e8a1)
Location: include/linux/blk_types.h:269
Inline: True
Inline callers:
  - block/elevator.c:elv_dispatch_sort
  - block/elevator.c:elv_dispatch_sort
```
```
In block/blk-core.c (ffffffff81425f5c)
Location: include/linux/blk_types.h:269
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-map.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In block/blk-merge.c (ffffffff8142dd73)
Location: include/linux/blk_types.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In block/bounce.c (ffffffff81442d87)
Location: include/linux/blk_types.h:269
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In block/blk-throttle.c (ffffffff8144ba41)
Location: include/linux/blk_types.h:269
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/deadline-iosched.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff8160b3f1)
Location: include/linux/blk_types.h:269
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8165a08e)
Location: include/linux/blk_types.h:269
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In drivers/md/md.c (ffffffff81739cf1)
Location: include/linux/blk_types.h:269
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff8174e59a)
Location: include/linux/blk_types.h:269
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/blk_types.h:269
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff8175ab99)
Location: include/linux/blk_types.h:269
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_start_request
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
In kernel/power/swap.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In block/elevator.c (ffffffff81448ec1)
Location: include/linux/blk_types.h:277
Inline: True
Inline callers:
  - block/elevator.c:elv_dispatch_sort
  - block/elevator.c:elv_dispatch_sort
```
```
In block/blk-core.c (ffffffff814513cc)
Location: include/linux/blk_types.h:277
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-map.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In block/blk-merge.c (ffffffff81458f9f)
Location: include/linux/blk_types.h:277
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In block/bounce.c (ffffffff8146f7fe)
Location: include/linux/blk_types.h:277
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In block/blk-throttle.c (ffffffff81477f6a)
Location: include/linux/blk_types.h:277
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/deadline-iosched.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81673cbc)
Location: include/linux/blk_types.h:277
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff816c32c4)
Location: include/linux/blk_types.h:277
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In drivers/md/md.c (ffffffff817b0ae5)
Location: include/linux/blk_types.h:277
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff817c05bb)
Location: include/linux/blk_types.h:277
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/blk_types.h:277
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff817ccdc7)
Location: include/linux/blk_types.h:277
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_start_request
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
In kernel/power/swap.c (ffffffff810ed990)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:373
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/blk_types.h:373
Inline: True
```
```
In block/bio.c (ffffffff8147b3bb)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/elevator.c (ffffffff8147bef9)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - block/elevator.c:elv_dispatch_sort
  - block/elevator.c:elv_dispatch_sort
```
```
In block/blk-core.c (ffffffff8148372d)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (0)
Location: include/linux/blk_types.h:373
Inline: True
```
```
In block/blk-merge.c (ffffffff8148c50d)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (ffffffff8148e30b)
Location: include/linux/blk_types.h:373
Inline: True
```
```
In block/bounce.c (ffffffff814a3af5)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:373
Inline: True
```
```
In block/bsg.c (ffffffff814a4d6c)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (ffffffff814ac5e5)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/deadline-iosched.c (0)
Location: include/linux/blk_types.h:373
Inline: True
```
```
In block/cfq-iosched.c (ffffffff814b462d)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_remove_request
```
```
In block/bio-integrity.c (ffffffff814b6369)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff814b83b3)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (ffffffff816ace20)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff816afaa5)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f0743)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
```
```
In drivers/scsi/sd.c (ffffffff8170069b)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81703dc2)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff817174f0)
Location: include/linux/blk_types.h:373
Inline: True
```
```
In drivers/md/md.c (ffffffff817f53bd)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff818075d4)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (ffffffff8181245a)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81812ed2)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (ffffffff81815ba6)
Location: include/linux/blk_types.h:373
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_start_request
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
In kernel/power/swap.c (ffffffff810f9000)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:381
Inline: True
```
```
In block/bio.c (ffffffff8149965b)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (ffffffff8149eeed)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (0)
Location: include/linux/blk_types.h:381
Inline: True
```
```
In block/blk-merge.c (ffffffff814a60dd)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (ffffffff814a7be0)
Location: include/linux/blk_types.h:381
Inline: True
```
```
In block/bounce.c (ffffffff814be1c0)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:381
Inline: True
```
```
In block/bsg.c (ffffffff814bf82c)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (ffffffff814c6994)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:381
Inline: True
```
```
In block/bio-integrity.c (ffffffff814c9c75)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff814cc3a1)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (ffffffff816cd16d)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff816cfbf2)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817156ed)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff817234b8)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81726355)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81739b40)
Location: include/linux/blk_types.h:381
Inline: True
```
```
In drivers/md/md.c (ffffffff81820f4d)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff818336ff)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (ffffffff8183e3da)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff8183ed92)
Location: include/linux/blk_types.h:381
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (ffffffff81841ec1)
Location: include/linux/blk_types.h:381
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
In kernel/power/swap.c (ffffffff81101703)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:382
Inline: True
```
```
In block/bio.c (ffffffff814c77e5)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (ffffffff814ccfb8)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-map.c (ffffffff814d1b00)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (ffffffff814d23b1)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (ffffffff814d8728)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/bounce.c (0)
Location: include/linux/blk_types.h:382
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:382
Inline: True
```
```
In block/bsg.c (ffffffff814edfe4)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (ffffffff814f51d4)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:382
Inline: True
```
```
In block/bio-integrity.c (ffffffff814f8599)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff814fab51)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (ffffffff8170929e)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff8170b58b)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750ec0)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff8175eaa5)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81761a84)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81775b4f)
Location: include/linux/blk_types.h:382
Inline: True
```
```
In drivers/md/md.c (ffffffff8186336a)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81875639)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (ffffffff818810f2)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81881aaf)
Location: include/linux/blk_types.h:382
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (ffffffff81884cfd)
Location: include/linux/blk_types.h:382
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
In kernel/power/swap.c (ffffffff8110db33)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio.c (ffffffff814e06f5)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (ffffffff814e6297)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-map.c (ffffffff814eaeb0)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (ffffffff814eb731)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (ffffffff814f1ad8)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/bounce.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bsg.c (ffffffff8150748b)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (ffffffff8150e8a4)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio-integrity.c (ffffffff81516319)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff81518a91)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (ffffffff8172d59e)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff8172f88b)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff8177512e)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff817821f2)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81785a74)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81799abf)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/md/md.c (ffffffff81894f13)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff818a73e9)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (ffffffff818b2fbf)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b394f)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (ffffffff818b6d20)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In kernel/power/swap.c (ffffffff81118b53)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In block/blk-core.c (ffffffff815454f3)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-map.c (ffffffff81549fcb)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:__blk_rq_unmap_user
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In block/blk-mq.c (ffffffff815512bb)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/bounce.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In block/bsg.c (ffffffff8156867b)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (ffffffff8156fe67)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In block/bio-integrity.c (ffffffff81576a99)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff81579181)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In block/blk-crypto-fallback.c (ffffffff81582e37)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/block/loop.c (ffffffff817e9442)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff817ee377)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff81837cbe)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/scsi/sd.c (ffffffff81843d54)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81849cee)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/md.c (ffffffff81962447)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8197705b)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - drivers/md/dm.c:end_io_acct
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (ffffffff819835ff)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81984215)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/md/dm-rq.c (ffffffff819875da)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In kernel/power/swap.c (ffffffff81114623)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:479
Inline: True
```
```
In block/blk-core.c (ffffffff81561b53)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-map.c (ffffffff81565d7b)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
```
```
In block/blk-merge.c (ffffffff8156961c)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff8156f143)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/bounce.c (0)
Location: include/linux/blk_types.h:479
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:479
Inline: True
```
```
In block/bsg.c (ffffffff81582fbb)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-cgroup.c (0)
Location: include/linux/blk_types.h:479
Inline: True
```
```
In block/blk-throttle.c (ffffffff8158acb3)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:479
Inline: True
```
```
In block/bio-integrity.c (ffffffff81593726)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff81595d51)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In block/blk-crypto-fallback.c (ffffffff8159fcd7)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/block/loop.c (ffffffff817fdec2)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81802c77)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff81848582)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/scsi/sd.c (ffffffff81854074)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8185a20b)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/md.c (ffffffff81968d7c)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8197bbbb)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm.c:end_io_acct
```
```
In drivers/md/dm-io.c (ffffffff8198771f)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81988308)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/md/dm-rq.c (ffffffff8198b576)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In kernel/power/swap.c (ffffffff81114de3)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:453
Inline: True
```
```
In block/blk-core.c (ffffffff8156a2b3)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-map.c (ffffffff8156e0ff)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
```
```
In block/blk-merge.c (ffffffff8157158c)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff81576ca5)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:453
Inline: True
```
```
In block/bsg.c (ffffffff81589de6)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-cgroup.c (0)
Location: include/linux/blk_types.h:453
Inline: True
```
```
In block/blk-throttle.c (ffffffff8159179b)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:453
Inline: True
```
```
In block/bio-integrity.c (ffffffff8159a50d)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff8159cb91)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In block/blk-crypto-fallback.c (ffffffff815a6ac7)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/block/loop.c (ffffffff817e2a72)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff817e72f7)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182aac6)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/scsi/sd.c (ffffffff81837ab4)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8183d215)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/md.c (ffffffff8194ce3c)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff819614d0)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-io.c (ffffffff8196bdf3)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196ca10)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/md/dm-rq.c (ffffffff8196fc66)
Location: include/linux/blk_types.h:453
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In kernel/power/swap.c (ffffffff81135463)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:444
Inline: True
```
```
In block/blk-core.c (ffffffff815cd995)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-map.c (ffffffff815d25bf)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
```
```
In block/blk-merge.c (ffffffff815d5c4c)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff815db94b)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-cgroup.c (0)
Location: include/linux/blk_types.h:444
Inline: True
```
```
In block/blk-throttle.c (ffffffff815f89d4)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/mq-deadline.c (ffffffff81600241)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_limit_depth
```
```
In block/bio-integrity.c (ffffffff816026ed)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff81605241)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In block/blk-crypto-fallback.c (ffffffff8160f5f1)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/block/loop.c (ffffffff8186ffea)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81873347)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:444
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b6596)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/scsi/scsi_bsg.c (ffffffff818c0cc3)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff818c45ad)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff818c9bbe)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/md.c (ffffffff819f221c)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81a0b0dd)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_io_dec_pending
```
```
In drivers/md/dm-io.c (ffffffff81a142b3)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81a14d40)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/md/dm-rq.c (ffffffff81a185a2)
Location: include/linux/blk_types.h:444
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In kernel/power/swap.c (ffffffff81157950)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:476
Inline: True
```
```
In block/blk-core.c (ffffffff81679639)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-map.c (ffffffff8167e2e1)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
```
```
In block/blk-merge.c (ffffffff816819bd)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff81689870)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-cgroup.c (0)
Location: include/linux/blk_types.h:476
Inline: True
```
```
In block/blk-throttle.c (ffffffff816aa9ce)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
```
```
In block/mq-deadline.c (ffffffff816b2966)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_limit_depth
```
```
In block/bio-integrity.c (ffffffff816b526e)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff816b8a53)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In block/blk-crypto-fallback.c (ffffffff816c3f13)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/block/loop.c (ffffffff819b75d7)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/block/xen-blkfront.c (ffffffff819bd28a)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:476
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a01acf)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/scsi/scsi_bsg.c (ffffffff81a0d369)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff81a11213)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81a16f12)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/md.c (ffffffff81b5b431)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81b6ff95)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_acct
```
```
In drivers/md/dm-io.c (ffffffff81b7caf3)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81b7d800)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/md/dm-rq.c (ffffffff81b812d6)
Location: include/linux/blk_types.h:476
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In kernel/power/swap.c (ffffffff8118883c)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:475
Inline: True
```
```
In block/blk-core.c (ffffffff817358c8)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-map.c (ffffffff8173afc1)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:475
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blk_types.h:475
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/blk_types.h:475
Inline: True
```
```
In block/blk-throttle.c (ffffffff8176946c)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
```
```
In block/mq-deadline.c (ffffffff81771ec6)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_limit_depth
```
```
In block/bio-integrity.c (ffffffff81774f54)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff81778db3)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In block/blk-crypto-fallback.c (ffffffff81785403)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/block/loop.c (ffffffff81b2c8d7)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81b3295a)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:475
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b8012f)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/scsi/scsi_bsg.c (ffffffff81b8d1b9)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff81b914a3)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81b97d72)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/md.c (ffffffff81cf4e01)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81d0c6a5)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_acct
```
```
In drivers/md/dm-io.c (ffffffff81d1a9bf)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d1b750)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/md/dm-rq.c (ffffffff81d1f606)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In kernel/power/swap.c (ffffffff811999fc)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:480
Inline: True
```
```
In block/blk-core.c (ffffffff81771de5)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-map.c (ffffffff81777855)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:480
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blk_types.h:480
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/blk_types.h:480
Inline: True
```
```
In block/blk-throttle.c (ffffffff817a8633)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
```
```
In block/mq-deadline.c (ffffffff817b1196)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_limit_depth
```
```
In block/bio-integrity.c (ffffffff817b4c71)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff817b89e3)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In block/blk-crypto-fallback.c (ffffffff817c5763)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/block/loop.c (ffffffff81b7cc35)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81b85e1a)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:480
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd4191)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/scsi/scsi_bsg.c (ffffffff81be11ca)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff81be79cf)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81bee2f1)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/md.c (ffffffff81d5cc11)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81d76a05)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_acct
```
```
In drivers/md/dm-io.c (ffffffff81d83b1f)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d848c0)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/md/dm-rq.c (ffffffff81d887e6)
Location: include/linux/blk_types.h:480
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In kernel/power/swap.c (ffffffff811a8a5c)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:479
Inline: True
```
```
In block/blk-core.c (ffffffff817b4122)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-map.c (ffffffff817b9a75)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:479
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blk_types.h:479
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/blk_types.h:479
Inline: True
```
```
In block/blk-throttle.c (ffffffff817ec3a3)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
```
```
In block/mq-deadline.c (ffffffff817f4fa6)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_limit_depth
```
```
In block/bio-integrity.c (ffffffff817f8d1a)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-wbt.c (ffffffff817fd423)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In block/blk-crypto-fallback.c (ffffffff8180a453)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/block/loop.c (ffffffff81bd0b63)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd9d2a)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:479
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28e01)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/scsi/scsi_bsg.c (ffffffff81c361fa)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff81c3cd4c)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81c439fe)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/md.c (ffffffff81e15cb1)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81e2dc35)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_acct
```
```
In drivers/md/dm-io.c (ffffffff81e3b1ff)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3c080)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/md/dm-rq.c (ffffffff81e3fef6)
Location: include/linux/blk_types.h:479
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio.c (ffff8000105dd258)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (ffff8000105e389c)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-map.c (ffff8000105e95e8)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (ffff8000105ea16c)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (ffff8000105f1144)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bsg.c (ffff80001060a744)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (ffff800010612490)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio-integrity.c (ffff80001061d550)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffff800010620564)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (ffff800010922c6c)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffff8000109265f8)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffff800010979278)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffff800010988f1c)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffff80001098c348)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffff8000109a1408)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/md/md.c (ffff800010ae7eec)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffff800010afe774)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (ffff800010b0a718)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0b608)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (ffff800010b0ed28)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
```
In drivers/mmc/core/block.c (ffff800010b42470)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_data_prep
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
In kernel/power/swap.c (c03c0a44)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio.c (c078a6b4)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (c0790bb8)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-map.c (c0795d1c)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (c0796730)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (c079d184)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/bounce.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bsg.c (c07b5584)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (c07bcc48)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio-integrity.c (c07c5140)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (c07c8010)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (c0a08980)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (c0a4d090)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (c0a5ae58)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (c0a5e6a4)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (c0a74708)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/md/md.c (c0bcb6ac)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/md/dm-io.c (c0be8ae8)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (c0be9a84)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/mmc/core/block.c (c0c1a9e4)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_data_prep
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
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio.c (c00000000076e910)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (c0000000007772d4)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-map.c (c00000000077e5e8)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (c00000000077f114)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (c000000000787e80)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bsg.c (c0000000007a5e7c)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (c0000000007b087c)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio-integrity.c (c0000000007bc340)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (c0000000007bfe34)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (c0000000009c9004)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (c000000000a33a3c)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (c000000000a48ea4)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (c000000000a4d2b8)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (c000000000a691d4)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/md/md.c (c000000000bd59a4)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (c000000000beae40)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (c000000000bfc2f8)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (c000000000bfd480)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (c000000000c01f68)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio.c (ffffffe000420404)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (ffffffe000425338)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-map.c (ffffffe000429e30)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (ffffffe00042a59e)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (ffffffe00042fd86)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bsg.c (ffffffe000443152)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (ffffffe000449b72)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio-integrity.c (ffffffe00045038e)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffe000452bd2)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (ffffffe0005a1e76)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0a36)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffe0005ed164)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffe0005f0906)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffe000602786)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/md/md.c (ffffffe0006dd4e6)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffe0006ed92a)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (ffffffe0006f868e)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f8fac)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (ffffffe0006fbf66)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
```
In drivers/mmc/core/block.c (ffffffe00071705e)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_data_prep
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
In kernel/power/swap.c (ffffffff81105d4f)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio.c (ffffffff814d8cd5)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (ffffffff814de877)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-map.c (ffffffff814e3490)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (ffffffff814e3d11)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (ffffffff814ea0b8)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/bounce.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bsg.c (ffffffff814ffa6b)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (ffffffff81506e84)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio-integrity.c (ffffffff8150e8f9)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff81511071)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (ffffffff816f337e)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff816f57fb)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff8172981e)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff817368e2)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8173a164)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/nvme/host/pci.c (ffffffff8174f59a)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
```
```
In drivers/ata/libata-scsi.c (ffffffff8175ebaf)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/md/md.c (ffffffff8183ad93)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8184d269)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (ffffffff81858e3f)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff818597cf)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (ffffffff8185cba0)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In kernel/power/swap.c (ffffffff810f6ff3)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio.c (ffffffff814c9685)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (ffffffff814cf217)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-map.c (ffffffff814d3e10)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (ffffffff814d45f1)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (ffffffff814da618)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/bounce.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bsg.c (ffffffff814eff7b)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (ffffffff814f7344)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio-integrity.c (ffffffff814fed29)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff81501391)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (ffffffff816cd47e)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/nvdimm/pmem.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/nvdimm/btt.c (ffffffff816ed597)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:btt_make_request
  - drivers/nvdimm/btt.c:btt_make_request
```
```
In drivers/nvdimm/blk.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81702c30)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81718582)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8171be04)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/nvme/host/pci.c (ffffffff8172f43a)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
```
```
In drivers/ata/libata-scsi.c (ffffffff8173ea4f)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/md/md.c (ffffffff81802403)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81814889)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (ffffffff8182044f)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81820ddf)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (ffffffff81824170)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In kernel/power/swap.c (ffffffff81104003)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio.c (ffffffff814d4d65)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (ffffffff814da907)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-map.c (ffffffff814df520)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (ffffffff814dfda1)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (ffffffff814e6148)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/bounce.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bsg.c (ffffffff814fbafb)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (ffffffff81502f14)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio-integrity.c (ffffffff8150a989)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff8150d101)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (ffffffff81720a5e)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81722d4b)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff817685ee)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81777072)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8177a8f4)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8178e93f)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/md/md.c (ffffffff8188a3c3)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8189c899)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (ffffffff818a846f)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a8dff)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (ffffffff818ac1d0)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In kernel/power/swap.c (ffffffff8110f3f3)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio.c (ffffffff814ed915)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (ffffffff814f3607)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-map.c (ffffffff814f8390)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (ffffffff814f8c01)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-mq.c (ffffffff814ff0cc)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/bounce.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bsg.c (ffffffff81514bab)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/blk-throttle.c (ffffffff8151c3a4)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/mq-deadline.c (0)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In block/bio-integrity.c (ffffffff81524029)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-wbt.c (ffffffff815267e1)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In drivers/block/loop.c (ffffffff8173be1e)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff8173e18b)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff81783d22)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81790e92)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81794724)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8a6f)
Location: include/linux/blk_types.h:390
Inline: True
```
```
In drivers/md/md.c (ffffffff818a9218)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff818b8ad9)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-io.c (ffffffff818c46af)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c520f)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:process_jobs
```
```
In drivers/md/dm-rq.c (ffffffff818c8420)
Location: include/linux/blk_types.h:390
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
</details>
</li>
</ul>

## Differences
