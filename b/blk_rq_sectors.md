# Function: <code>blk_rq_sectors</code>

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
In block/elevator.c (0)
Location: include/linux/blkdev.h:853
Inline: True
```
```
In block/blk-core.c (ffffffff813b50b7)
Location: include/linux/blkdev.h:853
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:perf_trace_block_rq_with_error
  - block/blk-core.c:trace_event_raw_event_block_rq_with_error
```
```
In block/blk-flush.c (0)
Location: include/linux/blkdev.h:853
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:853
Inline: True
```
```
In block/deadline-iosched.c (0)
Location: include/linux/blkdev.h:853
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/blkdev.h:853
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:853
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:853
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff815bb928)
Location: include/linux/blkdev.h:853
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/blkdev.h:853
Inline: True
```
```
In drivers/md/dm.c (ffffffff816a3cac)
Location: include/linux/blkdev.h:853
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_start_request
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
In block/elevator.c (ffffffff813f7e28)
Location: include/linux/blkdev.h:872
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_dispatch_add_tail
```
```
In block/blk-core.c (ffffffff813ff156)
Location: include/linux/blkdev.h:872
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_with_error
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_with_error
```
```
In block/blk-flush.c (ffffffff81401a6e)
Location: include/linux/blkdev.h:872
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff81405c15)
Location: include/linux/blkdev.h:872
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/cfq-iosched.c (ffffffff8142a0fa)
Location: include/linux/blkdev.h:872
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_activate_request
```
```
In drivers/block/xen-blkfront.c (ffffffff815cc368)
Location: include/linux/blkdev.h:872
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81608f5a)
Location: include/linux/blkdev.h:872
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81614198)
Location: include/linux/blkdev.h:872
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81618906)
Location: include/linux/blkdev.h:872
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff8170efb3)
Location: include/linux/blkdev.h:872
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:dm_start_request
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
In block/elevator.c (ffffffff81411842)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81418b94)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_with_error
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_with_error
```
```
In block/blk-flush.c (ffffffff8141b6cc)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff8141feb5)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/cfq-iosched.c (ffffffff81443f1e)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_activate_request
```
```
In drivers/block/xen-blkfront.c (ffffffff815f8f4c)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81638842)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81643b7d)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff816488e1)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8164957f)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff81740ff4)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_start_request
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
In block/elevator.c (ffffffff8141f2e5)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814267e4)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff8142970c)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff8142de5f)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff8142fa1c)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/cfq-iosched.c (ffffffff8145311b)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_activate_request
```
```
In drivers/block/xen-blkfront.c (ffffffff8160b7de)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164c9ff)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff8165a73a)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d204)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone
```
```
In drivers/scsi/sr.c (ffffffff8165de8c)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff8175ab86)
Location: include/linux/blkdev.h:1026
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_start_request
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
In block/elevator.c (ffffffff81449dc9)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff8144cc88)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff814548ec)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff8145907f)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff8145afa6)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/cfq-iosched.c (ffffffff8147dbbf)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_activate_request
```
```
In drivers/block/xen-blkfront.c (ffffffff816740a9)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b5d4f)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff816c3900)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6864)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone
```
```
In drivers/scsi/sr.c (ffffffff816c7478)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff817ccdb4)
Location: include/linux/blkdev.h:1039
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_start_request
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
In block/elevator.c (ffffffff8147cb18)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81484500)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff81487d35)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff8148c5d6)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/cfq-iosched.c (ffffffff814b3af3)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_activate_request
```
```
In drivers/block/xen-blkfront.c (ffffffff816b0083)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f20b7)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff816ff8dd)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81703d65)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff81815ba1)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_start_request
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
In block/elevator.c (ffffffff8149a70d)
Location: include/linux/blkdev.h:907
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff8149fbc9)
Location: include/linux/blkdev.h:907
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff814a1d63)
Location: include/linux/blkdev.h:907
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff814a6199)
Location: include/linux/blkdev.h:907
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In drivers/block/xen-blkfront.c (ffffffff816d01d0)
Location: include/linux/blkdev.h:907
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81714a37)
Location: include/linux/blkdev.h:907
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff817230c8)
Location: include/linux/blkdev.h:907
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81726225)
Location: include/linux/blkdev.h:907
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff81841eb3)
Location: include/linux/blkdev.h:907
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
In block/elevator.c (ffffffff814c87d8)
Location: include/linux/blkdev.h:924
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814cdcf5)
Location: include/linux/blkdev.h:924
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff814cfe66)
Location: include/linux/blkdev.h:924
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff814d4089)
Location: include/linux/blkdev.h:924
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In drivers/block/xen-blkfront.c (ffffffff8170bcf4)
Location: include/linux/blkdev.h:924
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750255)
Location: include/linux/blkdev.h:924
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff8176033e)
Location: include/linux/blkdev.h:924
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81761958)
Location: include/linux/blkdev.h:924
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff81884ced)
Location: include/linux/blkdev.h:924
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
In block/elevator.c (ffffffff814e18f8)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814e7015)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff814e9206)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff814ed3b9)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814eebad)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffff8151010b)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff8172fff4)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774445)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff8178429e)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81785948)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff818b6d0d)
Location: include/linux/blkdev.h:942
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
In block/elevator.c (ffffffff81540468)
Location: include/linux/blkdev.h:960
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81545f75)
Location: include/linux/blkdev.h:960
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff815481d9)
Location: include/linux/blkdev.h:960
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff8154cf49)
Location: include/linux/blkdev.h:960
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff8154fc99)
Location: include/linux/blkdev.h:960
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffff81571200)
Location: include/linux/blkdev.h:960
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff817ed8e2)
Location: include/linux/blkdev.h:960
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_discard_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff81837937)
Location: include/linux/blkdev.h:960
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81843d2c)
Location: include/linux/blkdev.h:960
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81849c8d)
Location: include/linux/blkdev.h:960
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff819875ca)
Location: include/linux/blkdev.h:960
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In block/elevator.c (ffffffff8155cc08)
Location: include/linux/blkdev.h:1008
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81bf2650)
Location: include/linux/blkdev.h:1008
Inline: True
Inline callers:
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff81563f19)
Location: include/linux/blkdev.h:1008
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff81567759)
Location: include/linux/blkdev.h:1008
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
```
```
In block/blk-mq.c (ffffffff8156c0bb)
Location: include/linux/blkdev.h:1008
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffff815905df)
Location: include/linux/blkdev.h:1008
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff81802212)
Location: include/linux/blkdev.h:1008
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_discard_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff81848303)
Location: include/linux/blkdev.h:1008
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff8185406d)
Location: include/linux/blkdev.h:1008
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8185a1b0)
Location: include/linux/blkdev.h:1008
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff8198b562)
Location: include/linux/blkdev.h:1008
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In block/elevator.c (ffffffff8156549b)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81be4582)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff8156c686)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff8156fddd)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
```
```
In block/blk-mq.c (ffffffff8157393b)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffff8159738c)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff817e7a54)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182b543)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81838387)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8183d1ba)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff8196fc52)
Location: include/linux/blkdev.h:991
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In block/elevator.c (ffffffff815c97d5)
Location: include/linux/blkdev.h:953
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81cd8024)
Location: include/linux/blkdev.h:953
Inline: True
Inline callers:
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff815d0b66)
Location: include/linux/blkdev.h:953
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff815d448a)
Location: include/linux/blkdev.h:953
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
```
```
In block/blk-mq.c (ffffffff815d7f38)
Location: include/linux/blkdev.h:953
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffff815fe9ba)
Location: include/linux/blkdev.h:953
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff81873a58)
Location: include/linux/blkdev.h:953
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b712e)
Location: include/linux/blkdev.h:953
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff818c4d36)
Location: include/linux/blkdev.h:953
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff818c9b60)
Location: include/linux/blkdev.h:953
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff81a18592)
Location: include/linux/blkdev.h:953
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In block/elevator.c (ffffffff81674a7e)
Location: include/linux/blk-mq.h:1023
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81677363)
Location: include/linux/blk-mq.h:1023
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff8167c3c3)
Location: include/linux/blk-mq.h:1023
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff816802d2)
Location: include/linux/blk-mq.h:1023
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff81687fc7)
Location: include/linux/blk-mq.h:1023
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_dump_rq_flags
```
```
In block/blk-iocost.c (ffffffff816b2211)
Location: include/linux/blk-mq.h:1023
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff819bda74)
Location: include/linux/blk-mq.h:1023
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02847)
Location: include/linux/blk-mq.h:1023
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81a11a6a)
Location: include/linux/blk-mq.h:1023
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81a16eb5)
Location: include/linux/blk-mq.h:1023
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff81b812c6)
Location: include/linux/blk-mq.h:1023
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In block/elevator.c (ffffffff817307be)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81733500)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff81738c53)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff8173d69d)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff817463a6)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_dump_rq_flags
```
```
In block/blk-iocost.c (ffffffff81771749)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In block/mq-deadline.c (ffffffff81773c06)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In drivers/block/xen-blkfront.c (ffffffff81b33154)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b810fc)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81b91d35)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81b97d15)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff81d1f5f6)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In block/elevator.c (ffffffff8176ca1e)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff8176f920)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff8177528a)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff81779c1d)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff8178374e)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_dump_rq_flags
```
```
In block/blk-iocost.c (ffffffff817b0a31)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In block/mq-deadline.c (ffffffff817b31ce)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In drivers/block/virtio_blk.c (ffffffff81b7ed01)
Location: include/linux/blk-mq.h:1054
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81b86684)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd4f99)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be29a4)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/scsi/sd.c (ffffffff81be8196)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81bee294)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff81d887d6)
Location: include/linux/blk-mq.h:1054
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In block/elevator.c (ffffffff817aec4e)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff817b1b8d)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff817b7595)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff817bbfed)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff817c5abe)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_dump_rq_flags
```
```
In block/blk-iocost.c (ffffffff817f4841)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In block/mq-deadline.c (ffffffff817f6d87)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In drivers/block/virtio_blk.c (ffffffff81bd33fc)
Location: include/linux/blk-mq.h:1051
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81bda553)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c29bf9)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c37b80)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/scsi/sd.c (ffffffff81c3d6b7)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81c439a1)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff81e3fee6)
Location: include/linux/blk-mq.h:1051
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In block/elevator.c (ffff8000105de9ec)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffff8000105e49c4)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffff8000105e7294)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffff8000105ebe80)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffff8000105eea8c)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffff8000106165fc)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/block/xen-blkfront.c (ffff80001092a4d0)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffff8000109784a8)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffff800010988f58)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffff80001098c204)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffff800010b0ed1c)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
```
In drivers/mmc/core/block.c (ffff800010b432bc)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_data_prep
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
In block/elevator.c (c078b98c)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (c0791bf4)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (c0793e94)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (c0798388)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (c0799d6c)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (c07c17c8)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/scsi/scsi_lib.c (c0a4c328)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (c0a5ae94)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (c0a5e5a0)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (c0bed108)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
```
In drivers/mmc/core/block.c (c0c1d2e4)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_data_prep
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
In block/elevator.c (c000000000770758)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_add
```
```
In block/blk-core.c (c0000000007788c4)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (c00000000077bbbc)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (c000000000781394)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (c00000000078389c)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (c0000000007b2a24)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/scsi/scsi_lib.c (c000000000a32a80)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (c000000000a4b5bc)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (c000000000a4d210)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (c000000000c01f68)
Location: include/linux/blkdev.h:942
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
In block/elevator.c (ffffffe0004215d6)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffe000426086)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffe0004280ec)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffe00042bb92)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffe00042d112)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffe00044b312)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dfeb4)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffe0005ed196)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffe0005f087a)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffe0006fbf4c)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
```
In drivers/mmc/core/block.c (ffffffe000718f56)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_data_prep
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
In block/elevator.c (ffffffff814d9ed8)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814df5f5)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff814e17e6)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff814e5999)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814e718d)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffff815086eb)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff816f5f64)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81728b35)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff8173898e)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8173a038)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff8185cb8d)
Location: include/linux/blkdev.h:942
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
In block/elevator.c (ffffffff814ca888)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814cff95)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff814d2176)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff814d5f49)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814d76fd)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffff814f8b9b)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/scsi/scsi_lib.c (ffffffff81701f65)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff8171a62e)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8171bcd8)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff8182415d)
Location: include/linux/blkdev.h:942
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
In block/elevator.c (ffffffff814d5f68)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814db685)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff814dd876)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff814e1a29)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814e321d)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffff8150477b)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff817234b4)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767905)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772a4a)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/scsi/sd.c (ffffffff8177911e)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8177a7c8)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff818ac1bd)
Location: include/linux/blkdev.h:942
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
In block/elevator.c (ffffffff814eeb68)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814f44f5)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-flush.c (ffffffff814f66d6)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-merge.c (ffffffff814fa8e9)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814fc0bc)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffff8151dd2b)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff8173e924)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81783045)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81792f3e)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sr.c (ffffffff817945f8)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff818c840d)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
</details>
</li>
</ul>

## Differences
