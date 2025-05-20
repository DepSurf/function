# Function: <code>req_op</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (ffffffff817308e5)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-core.c (ffffffff81733a6a)
Location: include/linux/blk-mq.h:206
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
In block/blk-map.c (ffffffff8173afa5)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_bio_alloc
  - block/blk-map.c:bio_copy_user_iov
```
```
In block/blk-merge.c (ffffffff8173d6b4)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff81744a1f)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_end_request
  - block/blk-mq.c:__blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_check_inflight
```
```
In block/blk-mq-sched.c (ffffffff8174e5ae)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
```
In block/blk-iocost.c (ffffffff8176c775)
Location: include/linux/blk-mq.h:206
Inline: True
```
```
In block/mq-deadline.c (ffffffff817734eb)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In block/blk-zoned.c (ffffffff81777cc5)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/blk-wbt.c (ffffffff81778da5)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In block/blk-mq-debugfs.c (ffffffff8177c437)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
```
In drivers/block/loop.c (ffffffff81b2c8d7)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/block/xen-blkfront.c (ffffffff81b341b7)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi.c (ffffffff81b75c4a)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81b77951)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7bd68)
Location: include/linux/blk-mq.h:206
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
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
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
In drivers/scsi/scsi_bsg.c (ffffffff81b8d1b9)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff81b921ba)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b97104)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
```
```
In drivers/scsi/sr.c (ffffffff81b97ab0)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81baf980)
Location: include/linux/blk-mq.h:206
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
```
```
In drivers/md/dm-rq.c (ffffffff81d1f606)
Location: include/linux/blk-mq.h:206
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
In block/elevator.c (ffffffff8176cb4b)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-map.c (ffffffff81777855)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_bio_alloc
  - block/blk-map.c:bio_copy_user_iov
```
```
In block/blk-merge.c (ffffffff8177ad4a)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff8178372a)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-stat.c (0)
Location: include/linux/blk-mq.h:197
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blk-mq.h:197
Inline: True
```
```
In block/blk-iocost.c (ffffffff817aac45)
Location: include/linux/blk-mq.h:197
Inline: True
```
```
In block/mq-deadline.c (ffffffff817b3ea1)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/mq-deadline.c:dd_request_merge
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:dd_merged_requests
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:dd_request_merged
```
```
In block/blk-zoned.c (ffffffff817b787b)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/blk-wbt.c (ffffffff817b89d5)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In block/blk-mq-debugfs.c (ffffffff817bbf37)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
```
In drivers/block/loop.c (ffffffff81b7cc35)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/block/virtio_blk.c (ffffffff81b802fc)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
```
```
In drivers/block/xen-blkfront.c (ffffffff81b876aa)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81bcb6e6)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd5225)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
```
In drivers/scsi/scsi_bsg.c (ffffffff81be11ca)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff81be86ca)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bed6a4)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
```
```
In drivers/scsi/sr.c (ffffffff81bee02f)
Location: include/linux/blk-mq.h:197
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff81d887e6)
Location: include/linux/blk-mq.h:197
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
In block/elevator.c (ffffffff817aed76)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-map.c (ffffffff817b9a75)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_bio_alloc
  - block/blk-map.c:bio_copy_user_iov
```
```
In block/blk-merge.c (ffffffff817bd12b)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff817c5a9a)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-stat.c (0)
Location: include/linux/blk-mq.h:191
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blk-mq.h:191
Inline: True
```
```
In block/blk-iocost.c (ffffffff817ee9f5)
Location: include/linux/blk-mq.h:191
Inline: True
```
```
In block/mq-deadline.c (ffffffff817f7a1a)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/mq-deadline.c:dd_request_merge
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:dd_merged_requests
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:dd_request_merged
```
```
In block/blk-zoned.c (ffffffff817fc0d7)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/blk-wbt.c (ffffffff817fd415)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_data_dir
```
```
In block/blk-mq-debugfs.c (ffffffff818005f7)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
```
In drivers/block/loop.c (ffffffff81bd0b63)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_complete_rq
```
```
In drivers/block/virtio_blk.c (ffffffff81bd413c)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
```
```
In drivers/block/xen-blkfront.c (ffffffff81bdb55a)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81c20316)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c29e81)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
```
In drivers/scsi/scsi_bsg.c (ffffffff81c361fa)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff81c3dc29)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c42d85)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
```
```
In drivers/scsi/sr.c (ffffffff81c4373c)
Location: include/linux/blk-mq.h:191
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/md/dm-rq.c (ffffffff81e3fef6)
Location: include/linux/blk-mq.h:191
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
