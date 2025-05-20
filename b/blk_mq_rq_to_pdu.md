# Function: <code>blk_mq_rq_to_pdu</code>

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
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:255
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/blk-mq.h:255
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff815af7a1)
Location: include/linux/blk-mq.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/md/dm.c (ffffffff816a10d6)
Location: include/linux/blk-mq.h:255
Inline: True
Inline callers:
  - drivers/md/dm.c:end_clone_request
  - drivers/md/dm.c:dm_requeue_original_request
  - drivers/md/dm.c:dm_softirq_done
  - drivers/md/dm.c:map_request
  - drivers/md/dm.c:map_request
  - drivers/md/dm.c:dm_start_request
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_mq_queue_rq
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
In drivers/block/loop.c (ffffffff815c627f)
Location: include/linux/blk-mq.h:262
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/virtio_blk.c (ffffffff815c7635)
Location: include/linux/blk-mq.h:262
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtio_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff816079b0)
Location: include/linux/blk-mq.h:262
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/md/dm-rq.c (ffffffff8170f8f6)
Location: include/linux/blk-mq.h:262
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:dm_complete_request
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
In drivers/block/loop.c (ffffffff815f47db)
Location: include/linux/blk-mq.h:256
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff816372c5)
Location: include/linux/blk-mq.h:256
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/md/dm-rq.c (ffffffff817418fc)
Location: include/linux/blk-mq.h:256
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:dm_complete_request
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:279
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:279
Inline: True
```
```
In block/bsg-lib.c (ffffffff814457a7)
Location: include/linux/blk-mq.h:279
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_init_rq
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_softirq_done
```
```
In drivers/block/loop.c (ffffffff81608a7d)
Location: include/linux/blk-mq.h:279
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:279
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blk-mq.h:279
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164ce25)
Location: include/linux/blk-mq.h:279
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:279
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:279
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:279
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:279
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:279
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff8175b0c1)
Location: include/linux/blk-mq.h:279
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:297
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:297
Inline: True
```
```
In block/bsg-lib.c (ffffffff814721f6)
Location: include/linux/blk-mq.h:297
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_request_fn
```
```
In drivers/block/loop.c (ffffffff8167131d)
Location: include/linux/blk-mq.h:297
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:297
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816b11ba)
Location: include/linux/blk-mq.h:297
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b61da)
Location: include/linux/blk-mq.h:297
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_unprep_fn
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:297
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:297
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:297
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:297
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:297
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff817cd314)
Location: include/linux/blk-mq.h:297
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:312
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:312
Inline: True
```
```
In block/bsg-lib.c (ffffffff814a6745)
Location: include/linux/blk-mq.h:312
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_request_fn
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:312
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:312
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816ed4c5)
Location: include/linux/blk-mq.h:312
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ef20c)
Location: include/linux/blk-mq.h:312
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_unprep_fn
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:312
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:312
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:312
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:312
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:312
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff818160e6)
Location: include/linux/blk-mq.h:312
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:347
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:347
Inline: True
```
```
In block/bsg-lib.c (ffffffff814c0675)
Location: include/linux/blk-mq.h:347
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:347
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:347
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81710ff5)
Location: include/linux/blk-mq.h:347
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81715019)
Location: include/linux/blk-mq.h:347
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:347
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:347
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:347
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:347
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:347
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81841bd8)
Location: include/linux/blk-mq.h:347
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:346
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:346
Inline: True
```
```
In block/bsg-lib.c (ffffffff814eed85)
Location: include/linux/blk-mq.h:346
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:346
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:346
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8174c415)
Location: include/linux/blk-mq.h:346
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff817507fa)
Location: include/linux/blk-mq.h:346
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:346
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:346
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:346
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:346
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:346
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81884a08)
Location: include/linux/blk-mq.h:346
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg-lib.c (ffffffff81508235)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81770595)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774a1d)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff818b6b98)
Location: include/linux/blk-mq.h:354
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:563
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:563
Inline: True
```
```
In block/bsg-lib.c (ffffffff81569425)
Location: include/linux/blk-mq.h:563
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:563
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:563
Inline: True
```
```
In drivers/scsi/hosts.c (ffffffff8182ecd5)
Location: include/linux/blk-mq.h:563
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:__scsi_host_busy_iter_fn
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_error.c (ffffffff81832e85)
Location: include/linux/blk-mq.h:563
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81835cfe)
Location: include/linux/blk-mq.h:563
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:563
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:563
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:563
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:563
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:563
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81987458)
Location: include/linux/blk-mq.h:563
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:568
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:568
Inline: True
```
```
In block/bsg-lib.c (ffffffff81583cf5)
Location: include/linux/blk-mq.h:568
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (ffffffff817fdd75)
Location: include/linux/blk-mq.h:568
Inline: True
Inline callers:
  - drivers/block/loop.c:do_req_filebacked
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:568
Inline: True
```
```
In drivers/scsi/hosts.c (ffffffff8183fd15)
Location: include/linux/blk-mq.h:568
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:__scsi_host_busy_iter_fn
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_error.c (ffffffff81843a85)
Location: include/linux/blk-mq.h:568
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff8184680e)
Location: include/linux/blk-mq.h:568
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:568
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:568
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:568
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:568
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:568
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff8198b3f8)
Location: include/linux/blk-mq.h:568
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:585
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:585
Inline: True
```
```
In block/bsg-lib.c (ffffffff8158aaf5)
Location: include/linux/blk-mq.h:585
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:585
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:585
Inline: True
```
```
In drivers/scsi/hosts.c (ffffffff81822f95)
Location: include/linux/blk-mq.h:585
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:__scsi_host_busy_iter_fn
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_error.c (ffffffff81826c35)
Location: include/linux/blk-mq.h:585
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff818287be)
Location: include/linux/blk-mq.h:585
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:585
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:585
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:585
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:585
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:585
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff8196fae8)
Location: include/linux/blk-mq.h:585
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
In block/bsg-lib.c (ffffffff815efbc5)
Location: include/linux/blk-mq.h:595
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (ffffffff8186fe73)
Location: include/linux/blk-mq.h:595
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:595
Inline: True
```
```
In drivers/scsi/hosts.c (ffffffff818ad8b5)
Location: include/linux/blk-mq.h:595
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:__scsi_host_busy_iter_fn
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:595
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff818b2585)
Location: include/linux/blk-mq.h:595
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b40be)
Location: include/linux/blk-mq.h:595
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:595
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (0)
Location: include/linux/blk-mq.h:595
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:595
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/blk-mq.h:595
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:595
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:595
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81a18428)
Location: include/linux/blk-mq.h:595
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
In block/bsg-lib.c (ffffffff816a0d1b)
Location: include/linux/blk-mq.h:913
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_transport_sg_io_fn
```
```
In drivers/block/loop.c (ffffffff819b6813)
Location: include/linux/blk-mq.h:913
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:do_req_filebacked
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:913
Inline: True
```
```
In drivers/scsi/hosts.c (ffffffff819f8735)
Location: include/linux/blk-mq.h:913
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:__scsi_host_busy_iter_fn
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:913
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff819fd645)
Location: include/linux/blk-mq.h:913
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff819ff19e)
Location: include/linux/blk-mq.h:913
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:913
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (0)
Location: include/linux/blk-mq.h:913
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/blk-mq.h:913
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:913
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:913
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81b81138)
Location: include/linux/blk-mq.h:913
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
In block/bsg-lib.c (ffffffff8175f8bb)
Location: include/linux/blk-mq.h:941
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_transport_sg_io_fn
```
```
In drivers/block/loop.c (ffffffff81b2ba33)
Location: include/linux/blk-mq.h:941
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:do_req_filebacked
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/scsi/hosts.c (ffffffff81b76125)
Location: include/linux/blk-mq.h:941
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:__scsi_host_busy_iter_fn
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7ba45)
Location: include/linux/blk-mq.h:941
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7d7ae)
Location: include/linux/blk-mq.h:941
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81d1f468)
Location: include/linux/blk-mq.h:941
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
In block/bsg-lib.c (ffffffff8179e79e)
Location: include/linux/blk-mq.h:941
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_transport_sg_io_fn
```
```
In drivers/block/loop.c (ffffffff81b7bd33)
Location: include/linux/blk-mq.h:941
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:do_req_filebacked
```
```
In drivers/block/virtio_blk.c (ffffffff81b7fa41)
Location: include/linux/blk-mq.h:941
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/scsi/hosts.c (ffffffff81bc9db5)
Location: include/linux/blk-mq.h:941
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:__scsi_host_busy_iter_fn
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcf755)
Location: include/linux/blk-mq.h:941
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd154e)
Location: include/linux/blk-mq.h:941
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:941
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81d88648)
Location: include/linux/blk-mq.h:941
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
In block/bsg-lib.c (ffffffff817e221a)
Location: include/linux/blk-mq.h:938
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_transport_sg_io_fn
```
```
In drivers/block/loop.c (ffffffff81bcfd63)
Location: include/linux/blk-mq.h:938
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:do_req_filebacked
```
```
In drivers/block/virtio_blk.c (ffffffff81bd3c29)
Location: include/linux/blk-mq.h:938
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:938
Inline: True
```
```
In drivers/scsi/hosts.c (ffffffff81c1e9e5)
Location: include/linux/blk-mq.h:938
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:__scsi_host_busy_iter_fn
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:938
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81c243b5)
Location: include/linux/blk-mq.h:938
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c261be)
Location: include/linux/blk-mq.h:938
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff81c334f2)
Location: include/linux/blk-mq.h:938
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/scsi/scsi_bsg.c (0)
Location: include/linux/blk-mq.h:938
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/linux/blk-mq.h:938
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:938
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:938
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81e3fd58)
Location: include/linux/blk-mq.h:938
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg-lib.c (ffff80001060ad08)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_complete
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffff800010973960)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffff800010978ad8)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/md/dm-rq.c (ffff800010b0ebf4)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
```
In drivers/mmc/core/block.c (ffff800010b43040)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
```
```
In drivers/mmc/core/queue.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg-lib.c (c07b5cd8)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_complete
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/scsi_error.c (c0a4844c)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (c0a4c978)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/md/dm-rq.c (c0becfd8)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
```
In drivers/mmc/core/block.c (c0c1ccb8)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
```
```
In drivers/mmc/core/queue.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg-lib.c (c0000000007a7404)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_complete
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/scsi_error.c (c000000000a2d4c8)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (c000000000a331d0)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/md/dm-rq.c (c000000000c01dc0)
Location: include/linux/blk-mq.h:354
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg-lib.c (ffffffe000443f46)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dc7a2)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0400)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffe0006fbe48)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
```
In drivers/mmc/core/block.c (ffffffe000718d40)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
```
```
In drivers/mmc/core/queue.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg-lib.c (ffffffff81500815)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81724c85)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff8172910d)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/nvme/host/multipath.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/nvme/host/lightnvm.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/nvme/host/pci.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff8185ca18)
Location: include/linux/blk-mq.h:354
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg-lib.c (ffffffff814f0d25)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816fe0b5)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff8170253d)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170e185)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_bsg_job_timeout
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/nvme/host/multipath.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/nvme/host/pci.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81823fe8)
Location: include/linux/blk-mq.h:354
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg-lib.c (ffffffff814fc8a5)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81763a55)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767edd)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff818ac048)
Location: include/linux/blk-mq.h:354
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
In block/scsi_ioctl.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In block/bsg-lib.c (ffffffff81515955)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - block/bsg-lib.c:bsg_queue_rq
```
```
In drivers/block/loop.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8177f0b5)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff8178361c)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/scsi_debugfs.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/blk-mq.h:354
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff818c8298)
Location: include/linux/blk-mq.h:354
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
</details>
</li>
</ul>

## Differences
