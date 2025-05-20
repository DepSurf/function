# Function: <code>blk_mq_rq_from_pdu</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:293
Inline: True
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
In block/bsg-lib.c (ffffffff814a6459)
Location: include/linux/blk-mq.h:308
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_teardown_job
```
```
In drivers/block/loop.c (ffffffff816ace1a)
Location: include/linux/blk-mq.h:308
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:308
Inline: True
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
In block/bsg-lib.c (ffffffff814c0489)
Location: include/linux/blk-mq.h:343
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_teardown_job
```
```
In drivers/block/loop.c (ffffffff816cd167)
Location: include/linux/blk-mq.h:343
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:343
Inline: True
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
In block/bsg-lib.c (ffffffff814eeba9)
Location: include/linux/blk-mq.h:342
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_teardown_job
```
```
In drivers/block/loop.c (ffffffff81709297)
Location: include/linux/blk-mq.h:342
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:342
Inline: True
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
In block/bsg-lib.c (ffffffff81508009)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_teardown_job
```
```
In drivers/block/loop.c (ffffffff8172d58c)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:350
Inline: True
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
In block/bsg-lib.c (ffffffff815691c9)
Location: include/linux/blk-mq.h:549
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
```
```
In drivers/block/loop.c (ffffffff817e9435)
Location: include/linux/blk-mq.h:549
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:549
Inline: True
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
In block/bsg-lib.c (ffffffff81583aa5)
Location: include/linux/blk-mq.h:554
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
```
```
In drivers/block/loop.c (ffffffff817fdeb5)
Location: include/linux/blk-mq.h:554
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:554
Inline: True
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
In block/bsg-lib.c (ffffffff8158a8b5)
Location: include/linux/blk-mq.h:571
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
```
```
In drivers/block/loop.c (ffffffff817e2a65)
Location: include/linux/blk-mq.h:571
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:571
Inline: True
```
```
In drivers/mmc/core/crypto.c (0)
Location: include/linux/blk-mq.h:571
Inline: True
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
In block/bsg-lib.c (ffffffff815ef835)
Location: include/linux/blk-mq.h:581
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
```
```
In drivers/block/loop.c (ffffffff8186ffdc)
Location: include/linux/blk-mq.h:581
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blk-mq.h:581
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blk-mq.h:581
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b535b)
Location: include/linux/blk-mq.h:581
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/linux/blk-mq.h:581
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:581
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8db4)
Location: include/linux/blk-mq.h:581
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sr.c (ffffffff818c9844)
Location: include/linux/blk-mq.h:581
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:581
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff818e1ca8)
Location: include/linux/blk-mq.h:581
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
```
```
In drivers/mmc/core/crypto.c (0)
Location: include/linux/blk-mq.h:581
Inline: True
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
In block/bsg-lib.c (ffffffff816a07e5)
Location: include/linux/blk-mq.h:899
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
```
```
In drivers/block/loop.c (ffffffff819b75d7)
Location: include/linux/blk-mq.h:899
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blk-mq.h:899
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blk-mq.h:899
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a01f95)
Location: include/linux/blk-mq.h:899
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/linux/blk-mq.h:899
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:899
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a16324)
Location: include/linux/blk-mq.h:899
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sr.c (ffffffff81a16bb5)
Location: include/linux/blk-mq.h:899
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:899
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff81a32cd8)
Location: include/linux/blk-mq.h:899
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
```
```
In drivers/mmc/core/crypto.c (0)
Location: include/linux/blk-mq.h:899
Inline: True
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
In block/bsg-lib.c (ffffffff8175f355)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
```
```
In drivers/block/loop.c (ffffffff81b2c8d7)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blk-mq.h:927
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blk-mq.h:927
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b80655)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/linux/blk-mq.h:927
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:927
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b97104)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sr.c (ffffffff81b97a15)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:927
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff81bb73e8)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
```
```
In drivers/mmc/core/crypto.c (0)
Location: include/linux/blk-mq.h:927
Inline: True
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
In block/bsg-lib.c (ffffffff8179e235)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
```
```
In drivers/block/loop.c (ffffffff81b7cc31)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/block/virtio_blk.c (ffffffff81b80230)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_done
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blk-mq.h:927
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blk-mq.h:927
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd46d5)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/linux/blk-mq.h:927
Inline: True
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be26e5)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/scsi/sd.c (ffffffff81be83c9)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bed6a4)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sr.c (ffffffff81bedf95)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:927
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff81c0e9f8)
Location: include/linux/blk-mq.h:927
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
```
```
In drivers/mmc/core/crypto.c (0)
Location: include/linux/blk-mq.h:927
Inline: True
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
In block/bsg-lib.c (ffffffff817e1cb5)
Location: include/linux/blk-mq.h:924
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
```
```
In drivers/block/loop.c (ffffffff81bd0b5f)
Location: include/linux/blk-mq.h:924
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4028)
Location: include/linux/blk-mq.h:924
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_done
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blk-mq.h:924
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blk-mq.h:924
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c29345)
Location: include/linux/blk-mq.h:924
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/linux/blk-mq.h:924
Inline: True
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c378c5)
Location: include/linux/blk-mq.h:924
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/scsi/sd.c (ffffffff81c3d936)
Location: include/linux/blk-mq.h:924
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c42d85)
Location: include/linux/blk-mq.h:924
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sr.c (ffffffff81c436a5)
Location: include/linux/blk-mq.h:924
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:924
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff81c63baa)
Location: include/linux/blk-mq.h:924
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
```
```
In drivers/mmc/core/crypto.c (0)
Location: include/linux/blk-mq.h:924
Inline: True
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
In block/bsg-lib.c (ffff80001060ac38)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_job_put
```
```
In drivers/block/loop.c (ffff800010922c64)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:350
Inline: True
```
```
In drivers/mmc/core/block.c (ffff800010b42348)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_cqe_req_done
```
```
In drivers/mmc/core/queue.c (ffff800010b44704)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_queue_map_sg
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
In block/bsg-lib.c (c07b5a60)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_job_put
```
```
In drivers/block/loop.c (c0a08964)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:350
Inline: True
```
```
In drivers/mmc/core/block.c (c0c1a8cc)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_cqe_req_done
```
```
In drivers/mmc/core/queue.c (c0c1e254)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_queue_map_sg
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
In block/bsg-lib.c (c0000000007a706c)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_job_put
```
```
In drivers/block/loop.c (c0000000009c8fec)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:350
Inline: True
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
In block/bsg-lib.c (ffffffe000443cf4)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_teardown_job
```
```
In drivers/block/loop.c (ffffffe0005a1e60)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:350
Inline: True
```
```
In drivers/mmc/core/block.c (ffffffe000716f7c)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_cqe_req_done
```
```
In drivers/mmc/core/queue.c (ffffffe000719fda)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_queue_map_sg
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
In block/bsg-lib.c (ffffffff815005e9)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_teardown_job
```
```
In drivers/block/loop.c (ffffffff816f336c)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:350
Inline: True
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
In block/bsg-lib.c (ffffffff814f0af9)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_teardown_job
```
```
In drivers/block/loop.c (ffffffff816cd46c)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:350
Inline: True
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
In block/bsg-lib.c (ffffffff814fc679)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_teardown_job
```
```
In drivers/block/loop.c (ffffffff81720a4c)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:350
Inline: True
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
In block/bsg-lib.c (ffffffff81515729)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_done
  - block/bsg-lib.c:bsg_teardown_job
```
```
In drivers/block/loop.c (ffffffff8173be0c)
Location: include/linux/blk-mq.h:350
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blk-mq.h:350
Inline: True
```
</details>
</li>
</ul>

## Differences
