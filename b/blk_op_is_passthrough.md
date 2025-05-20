# Function: <code>blk_op_is_passthrough</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8157304a)
Location: include/linux/blkdev.h:274
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
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
Location: include/linux/blkdev.h:246
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
In block/elevator.c (0)
Location: include/linux/blkdev.h:246
Inline: True
```
```
In block/blk-core.c (ffffffff815cd0d4)
Location: include/linux/blkdev.h:246
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
Location: include/linux/blkdev.h:246
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In block/blk-merge.c (ffffffff815d449f)
Location: include/linux/blkdev.h:246
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
```
```
In block/blk-mq.c (ffffffff815d7acc)
Location: include/linux/blkdev.h:246
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-sched.c (ffffffff815e0e8f)
Location: include/linux/blkdev.h:246
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:246
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:246
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81873909)
Location: include/linux/blkdev.h:246
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff818ad579)
Location: include/linux/blkdev.h:246
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff818b27bf)
Location: include/linux/blkdev.h:246
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
Location: include/linux/blkdev.h:246
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
Location: include/linux/blkdev.h:246
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
Location: include/linux/blkdev.h:223
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:223
Inline: True
```
```
In block/blk-core.c (ffffffff816775dd)
Location: include/linux/blkdev.h:223
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
Location: include/linux/blkdev.h:223
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff81688029)
Location: include/linux/blkdev.h:223
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
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-sched.c (ffffffff8168fa4e)
Location: include/linux/blkdev.h:223
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:223
Inline: True
```
```
In block/blk-zoned.c (ffffffff816b7ae9)
Location: include/linux/blkdev.h:223
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff819bd8f0)
Location: include/linux/blkdev.h:223
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff819f827a)
Location: include/linux/blkdev.h:223
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff819fd937)
Location: include/linux/blkdev.h:223
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
Location: include/linux/blkdev.h:223
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
Location: include/linux/blkdev.h:223
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
Location: include/linux/blkdev.h:255
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:255
Inline: True
```
```
In block/blk-core.c (ffffffff81733a6a)
Location: include/linux/blkdev.h:255
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
Location: include/linux/blkdev.h:255
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff81746407)
Location: include/linux/blkdev.h:255
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
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-sched.c (ffffffff8174e5ae)
Location: include/linux/blkdev.h:255
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:255
Inline: True
```
```
In block/blk-zoned.c (ffffffff81777cc8)
Location: include/linux/blkdev.h:255
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In drivers/block/xen-blkfront.c (ffffffff81b32fd0)
Location: include/linux/blkdev.h:255
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81b75c4a)
Location: include/linux/blkdev.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7bd68)
Location: include/linux/blkdev.h:255
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
Location: include/linux/blkdev.h:255
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
Location: include/linux/blkdev.h:255
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
Location: include/linux/blkdev.h:260
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff8176ca04)
Location: include/linux/blkdev.h:260
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff8176fe8a)
Location: include/linux/blkdev.h:260
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
Location: include/linux/blkdev.h:260
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
Location: include/linux/blkdev.h:260
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
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-sched.c (ffffffff8178a2f9)
Location: include/linux/blkdev.h:260
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/mq-deadline.c (ffffffff817b4132)
Location: include/linux/blkdev.h:260
Inline: True
```
```
In drivers/block/virtio_blk.c (ffffffff81b80278)
Location: include/linux/blkdev.h:260
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
```
```
In drivers/block/xen-blkfront.c (ffffffff81b864f0)
Location: include/linux/blkdev.h:260
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81bc956a)
Location: include/linux/blkdev.h:260
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcfa92)
Location: include/linux/blkdev.h:260
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
Location: include/linux/blkdev.h:260
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
Location: include/linux/blkdev.h:260
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
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff817aec34)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff817b20f7)
Location: include/linux/blkdev.h:262
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
Location: include/linux/blkdev.h:262
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
Location: include/linux/blkdev.h:262
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
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-sched.c (ffffffff817cca59)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/blk-cgroup.c (ffffffff817e5475)
Location: include/linux/blkdev.h:262
Inline: True
```
```
In block/mq-deadline.c (ffffffff817f80c8)
Location: include/linux/blkdev.h:262
Inline: True
```
```
In drivers/block/virtio_blk.c (ffffffff81bd40bf)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_poll
```
```
In drivers/block/xen-blkfront.c (ffffffff81bda3cb)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi.c (ffffffff81c1e15a)
Location: include/linux/blkdev.h:262
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81c246f2)
Location: include/linux/blkdev.h:262
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
Location: include/linux/blkdev.h:262
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
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
