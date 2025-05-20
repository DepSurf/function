# Function: <code>blk_rq_is_passthrough</code>

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
Location: include/linux/blkdev.h:253
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8141f6c9)
Location: include/linux/blkdev.h:253
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
Location: include/linux/blkdev.h:253
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
Location: include/linux/blkdev.h:253
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff8142dd38)
Location: include/linux/blkdev.h:253
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
Location: include/linux/blkdev.h:253
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff8160b16f)
Location: include/linux/blkdev.h:253
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81643d53)
Location: include/linux/blkdev.h:253
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816482e5)
Location: include/linux/blkdev.h:253
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164c57e)
Location: include/linux/blkdev.h:253
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8166f5bc)
Location: include/linux/blkdev.h:253
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
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8144a1e9)
Location: include/linux/blkdev.h:264
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
Location: include/linux/blkdev.h:264
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
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff81458f65)
Location: include/linux/blkdev.h:264
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
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814611d5)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In drivers/block/xen-blkfront.c (ffffffff81673a3b)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff816ace63)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816b13db)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b58fe)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff816d8b9c)
Location: include/linux/blkdev.h:264
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
Location: include/linux/blkdev.h:295
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8147cf39)
Location: include/linux/blkdev.h:295
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
Location: include/linux/blkdev.h:295
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
Location: include/linux/blkdev.h:295
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff8148c4c5)
Location: include/linux/blkdev.h:295
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff8148ddae)
Location: include/linux/blkdev.h:295
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff81494bf5)
Location: include/linux/blkdev.h:295
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/blk-zoned.c (ffffffff814b7f22)
Location: include/linux/blkdev.h:295
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff816afa4b)
Location: include/linux/blkdev.h:295
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff816e9383)
Location: include/linux/blkdev.h:295
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816ed71b)
Location: include/linux/blkdev.h:295
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f1b2b)
Location: include/linux/blkdev.h:295
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff81717d0b)
Location: include/linux/blkdev.h:295
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
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8149a692)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff8149f23f)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
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
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814a6095)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814a764a)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814aed35)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff814c7ef5)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff814cba22)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff816cfb98)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8170ce83)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81711217)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81714864)
Location: include/linux/blkdev.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8173a3fb)
Location: include/linux/blkdev.h:264
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
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814c8769)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814cd329)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
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
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814d3f75)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814d559b)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814dcff5)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff814f6787)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff814fa366)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff8170bb88)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81748563)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8174c637)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750173)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8177363b)
Location: include/linux/blkdev.h:262
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814e1889)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814e666d)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814ed2a5)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814ee87b)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814f68f7)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff815145b7)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff81518076)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff8172fe88)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8176c6b3)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff817707b7)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774363)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8179759b)
Location: include/linux/blkdev.h:269
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
Location: include/linux/blkdev.h:271
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff815403f9)
Location: include/linux/blkdev.h:271
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff815438e7)
Location: include/linux/blkdev.h:271
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
Location: include/linux/blkdev.h:271
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff8154ce25)
Location: include/linux/blkdev.h:271
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
Location: include/linux/blkdev.h:271
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff815573a6)
Location: include/linux/blkdev.h:271
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81575407)
Location: include/linux/blkdev.h:271
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff81578972)
Location: include/linux/blkdev.h:271
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff817ee982)
Location: include/linux/blkdev.h:271
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8182e9b6)
Location: include/linux/blkdev.h:271
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff818330a7)
Location: include/linux/blkdev.h:271
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836fc8)
Location: include/linux/blkdev.h:271
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8185cbfb)
Location: include/linux/blkdev.h:271
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
Location: include/linux/blkdev.h:267
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8155cb99)
Location: include/linux/blkdev.h:267
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff815607c7)
Location: include/linux/blkdev.h:267
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
Location: include/linux/blkdev.h:267
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff81567765)
Location: include/linux/blkdev.h:267
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
Location: include/linux/blkdev.h:267
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff81573a0f)
Location: include/linux/blkdev.h:267
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff815921f2)
Location: include/linux/blkdev.h:267
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff815951b6)
Location: include/linux/blkdev.h:267
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff81803282)
Location: include/linux/blkdev.h:267
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8183f9f6)
Location: include/linux/blkdev.h:267
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81843c97)
Location: include/linux/blkdev.h:267
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81847a38)
Location: include/linux/blkdev.h:267
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8186bccb)
Location: include/linux/blkdev.h:267
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
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8156542c)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81568e2d)
Location: include/linux/blkdev.h:262
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
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff8156fdfe)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
```
In block/blk-mq.c (ffffffff8157352c)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff8157baa4)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff815993a8)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff8159bf76)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff817e78f5)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81822c56)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81826e47)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182aab4)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8184e347)
Location: include/linux/blkdev.h:262
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811fcf4b)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/elevator.c (ffffffff815c9801)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff815cd0d4)
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
In block/blk-exec.c (ffffffff815d364d)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff815d449f)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
```
In block/blk-mq.c (ffffffff815d7acc)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff815e0e8f)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81601ac2)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_request
```
```
In block/blk-zoned.c (ffffffff816043f2)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff81873905)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff818ad579)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff818b27bf)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b794f)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (ffffffff818db9b7)
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8123701e)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff81674a61)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff816775dd)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
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
In block/blk-merge.c (ffffffff816802e5)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff81688029)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-sched.c (ffffffff8168fa4e)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff816b45a4)
Location: include/linux/blk-mq.h:203
Inline: True
```
```
In block/blk-zoned.c (ffffffff816b7ae6)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff819bd8ec)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff819f827a)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff819fd937)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02ec3)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2c380)
Location: include/linux/blk-mq.h:203
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
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
In kernel/trace/blktrace.c (ffffffff81283d6e)
Location: include/linux/blk-mq.h:211
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff817307a1)
Location: include/linux/blk-mq.h:211
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81733a6a)
Location: include/linux/blk-mq.h:211
Inline: True
Inline callers:
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
In block/blk-merge.c (ffffffff8173d6b4)
Location: include/linux/blk-mq.h:211
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff81746407)
Location: include/linux/blk-mq.h:211
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_end_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-sched.c (ffffffff8174e5ae)
Location: include/linux/blk-mq.h:211
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81773f3a)
Location: include/linux/blk-mq.h:211
Inline: True
```
```
In block/blk-zoned.c (ffffffff81777cc5)
Location: include/linux/blk-mq.h:211
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff81b32fcc)
Location: include/linux/blk-mq.h:211
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81b75c4a)
Location: include/linux/blk-mq.h:211
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7bd68)
Location: include/linux/blk-mq.h:211
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81a15)
Location: include/linux/blk-mq.h:211
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (ffffffff81baf980)
Location: include/linux/blk-mq.h:211
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812a0a1e)
Location: include/linux/blk-mq.h:202
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8176ca01)
Location: include/linux/blk-mq.h:202
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff8176fe8a)
Location: include/linux/blk-mq.h:202
Inline: True
Inline callers:
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
In block/blk-merge.c (ffffffff81779c34)
Location: include/linux/blk-mq.h:202
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff817837af)
Location: include/linux/blk-mq.h:202
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-sched.c (ffffffff8178a2f5)
Location: include/linux/blk-mq.h:202
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff817b412f)
Location: include/linux/blk-mq.h:202
Inline: True
```
```
In drivers/block/virtio_blk.c (ffffffff81b80278)
Location: include/linux/blk-mq.h:202
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
```
```
In drivers/block/xen-blkfront.c (ffffffff81b864f0)
Location: include/linux/blk-mq.h:202
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81bc956a)
Location: include/linux/blk-mq.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcfa92)
Location: include/linux/blk-mq.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd575a)
Location: include/linux/blk-mq.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff81c072b0)
Location: include/linux/blk-mq.h:202
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812bc14e)
Location: include/linux/blk-mq.h:196
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff817aec31)
Location: include/linux/blk-mq.h:196
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff817b20f7)
Location: include/linux/blk-mq.h:196
Inline: True
Inline callers:
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
In block/blk-merge.c (ffffffff817bc004)
Location: include/linux/blk-mq.h:196
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff817c5b1f)
Location: include/linux/blk-mq.h:196
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request
  - block/blk-mq.c:blk_mq_end_request
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-sched.c (ffffffff817cca55)
Location: include/linux/blk-mq.h:196
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff817f80c5)
Location: include/linux/blk-mq.h:196
Inline: True
```
```
In drivers/block/virtio_blk.c (ffffffff81bd40bf)
Location: include/linux/blk-mq.h:196
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_poll
```
```
In drivers/block/xen-blkfront.c (ffffffff81bda3cb)
Location: include/linux/blk-mq.h:196
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81c1e15a)
Location: include/linux/blk-mq.h:196
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81c246f2)
Location: include/linux/blk-mq.h:196
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a3ae)
Location: include/linux/blk-mq.h:196
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5c390)
Location: include/linux/blk-mq.h:196
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffff8000105de97c)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffff8000105e3dc8)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffff8000105ebd24)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffff8000105ee588)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffff8000105f6f60)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffff80001061939c)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffff80001061f6fc)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffff80001092a314)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffff80001096eca8)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffff800010973c3c)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffff80001097843c)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffff8000109a45dc)
Location: include/linux/blkdev.h:269
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (c078b918)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (c0790f6c)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (c0798224)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (c0799a18)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (c07a26c4)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (c07c3ce0)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (c07c721c)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/scsi.c (c0a44124)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (c0a486dc)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (c0a4c264)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (c0a7293c)
Location: include/linux/blkdev.h:269
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (c0000000007706d0)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (c0000000007779b4)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (c0000000007811dc)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (c0000000007833e0)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (c00000000078f468)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (c0000000007b87d8)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (c0000000007bf23c)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/scsi.c (c000000000a28094)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (c000000000a2d834)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (c000000000a32948)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (c000000000a665c0)
Location: include/linux/blkdev.h:269
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffe000421582)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffe000425662)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffe00042ba8c)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffe00042ce8e)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffe0004346b6)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffe00044ef98)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffe0004523bc)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/scsi.c (ffffffe0005d8e62)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dc9f6)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dfe6c)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffe00060161e)
Location: include/linux/blkdev.h:269
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814d9e69)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814dec4d)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814e5885)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814e6e5b)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814eeed7)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff8150cb97)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff81510656)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff816f5df8)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81720da3)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81724ea7)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81728a53)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8175c6ab)
Location: include/linux/blkdev.h:269
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814ca819)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814cf5ed)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814d5e35)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814d73cb)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814df417)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff814fcfc7)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff81500976)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/scsi/scsi.c (ffffffff816fa1d3)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816fe2d7)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81701e83)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8173c54b)
Location: include/linux/blkdev.h:269
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814d5ef9)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814dacdd)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814e1915)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814e2eeb)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff814eaf67)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81508c27)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff8150c6e6)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff81723348)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8175fb73)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81763c77)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767823)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff8178c41b)
Location: include/linux/blkdev.h:269
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff814eeaf9)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff814f3a68)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
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
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff814fa7d5)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff814fbd6b)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-sched.c (ffffffff81503f38)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff81522325)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-zoned.c (ffffffff81525dc6)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff8173e7b8)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff8177b1d3)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8177f2f7)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81782f63)
Location: include/linux/blkdev.h:269
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff817a626b)
Location: include/linux/blkdev.h:269
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
