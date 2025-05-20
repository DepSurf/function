# Function: <code>blk_rq_is_scsi</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81175abf)
Location: include/linux/blkdev.h:243
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8141f6c9)
Location: include/linux/blkdev.h:243
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:__elv_add_request
  - block/elevator.c:__elv_add_request
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_requeue_request
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81425cc1)
Location: include/linux/blkdev.h:243
Inline: True
Inline callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dequeue_request
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff8142b5e1)
Location: include/linux/blkdev.h:243
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff8142dd38)
Location: include/linux/blkdev.h:243
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq-sched.c (ffffffff814353a8)
Location: include/linux/blkdev.h:243
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff8160b16f)
Location: include/linux/blkdev.h:243
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81643d53)
Location: include/linux/blkdev.h:243
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816482e5)
Location: include/linux/blkdev.h:243
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164b24b)
Location: include/linux/blkdev.h:243
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8166f5bc)
Location: include/linux/blkdev.h:243
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In kernel/trace/blktrace.c (ffffffff81183137)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8144a1ed)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:__elv_add_request
  - block/elevator.c:__elv_add_request
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_requeue_request
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81450e3a)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_start_request
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff814567f1)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff81458f68)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff8145ad2a)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814611d8)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff81673a3f)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff816ace63)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816b13db)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b4593)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff816d8ba3)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In kernel/trace/blktrace.c (ffffffff811922a2)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8147cf3d)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:__elv_add_request
  - block/elevator.c:__elv_add_request
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_requeue_request
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814840f3)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_start_request
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff81489c31)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff8148c4c8)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff8148ddae)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff81494bf8)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/blk-zoned.c (ffffffff814b7f22)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff816afa4f)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff816e9383)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816ed71b)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f06d3)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff81717d0b)
Location: include/linux/blkdev.h:285
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In kernel/trace/blktrace.c (ffffffff8119fb26)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8149a695)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff8149f23f)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff814a3a28)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814a6098)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814a764a)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814aed38)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff814c7ef9)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff814cba22)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff816cfb9c)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8170ce83)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81711217)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff817152ba)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8173a3fb)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In kernel/trace/blktrace.c (ffffffff811ad877)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814c876d)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814cd329)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff814d1c42)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814d3f82)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814d559b)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814dcff8)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff814f678b)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff814fa366)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff8170bb8c)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81748563)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8174c637)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750a66)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8177363b)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (ffffffff811b90f2)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814e188d)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814e666d)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff814eafe8)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814ed2b2)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814ee87b)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814f68f7)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff815145bb)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff81518076)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff8172fe8c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8176c6b3)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff817707b7)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774ca1)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8179759b)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (ffffffff811d23c7)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff815403f9)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff815438e7)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff8154ad0d)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff8154ce25)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
  - block/blk-merge.c:attempt_back_merge
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff8154f526)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff815573a6)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81575407)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff81578972)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff817ee982)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8182e9b6)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff818330a7)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81837c1f)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8185cbfb)
Location: include/linux/blkdev.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (ffffffff811cee8b)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8155cb99)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff815607c7)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff81566acd)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff81567765)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
```
```
In block/blk-mq.c (ffffffff8156b85c)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff81573a0f)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff815921f2)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff815951b6)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff81803282)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8183f9f6)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81843c97)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff818485e7)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8186bccb)
Location: include/linux/blkdev.h:257
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (ffffffff811d061b)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8156542c)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81568e2d)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff8156f00d)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff8156fdfe)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
```
In block/blk-mq.c (ffffffff8157352c)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff8157baa4)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff815993a8)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff8159bf76)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff817e78f5)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81822c56)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81826e47)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182b915)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8184e347)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffff800010237c8c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffff8000105de980)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffff8000105e3dc8)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffff8000105e9a3c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffff8000105ebd28)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffff8000105ee588)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffff8000105f6f60)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffff8000106193a0)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffff80001061f6fc)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffff80001092a318)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffff80001096eca8)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffff800010973c3c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffff800010979054)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffff8000109a45dc)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (c04732e0)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (c078b918)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (c0790f6c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (c0795e7c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (c0798224)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (c0799a18)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (c07a26c4)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (c07c3ce0)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (c07c721c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/scsi.c (c0a44124)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (c0a486dc)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (c0a4cd24)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (c0a7293c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (c0000000002c36ec)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (c0000000007706d4)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (c0000000007779b4)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (c00000000077e7dc)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (c0000000007811e0)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (c0000000007833e0)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (c00000000078f468)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (c0000000007b87dc)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (c0000000007bf23c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/scsi.c (c000000000a28094)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (c000000000a2d834)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (c000000000a334e8)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (c000000000a665c0)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (ffffffe00018e60a)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffe000421584)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffe00042566c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffe000429f4e)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffe00042ba8e)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffe00042ce8e)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffe0004346b6)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffe00044ef9c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffe0004523bc)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/scsi.c (ffffffe0005d8e68)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dc9f6)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e05c2)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffe00060161e)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (ffffffff811b1712)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814d9e6d)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814dec4d)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff814e35c8)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814e5892)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814e6e5b)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814eeed7)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff8150cb9b)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff81510656)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff816f5dfc)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81720da3)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81724ea7)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81729391)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8175c6ab)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (ffffffff811a46b2)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814ca81d)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814cf5ed)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff814d3f43)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814d5e42)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814d73cb)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814df417)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff814fcfcb)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff81500976)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/scsi.c (ffffffff816fa1d3)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816fe2d7)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff817027bb)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8173c54b)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (ffffffff811af4e2)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814d5efd)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814dacdd)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff814df658)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814e1922)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814e2eeb)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814eaf67)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81508c2b)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff8150c6e6)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff8172334c)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8175fb73)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81763c77)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81768161)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8178c41b)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (ffffffff811bd4cd)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814eeafd)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814f3a68)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
```
In block/blk-exec.c (ffffffff814f84c8)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814fa7e2)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814fbd6b)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff81503f38)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81522329)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff81525dc6)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff8173e7bc)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8177b1d3)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8177f2f7)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff817838a1)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff817a626b)
Location: include/linux/blkdev.h:259
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
```
</details>
</li>
</ul>

## Differences
