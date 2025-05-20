# Function: <code>blk_mq_unquiesce_queue</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430d00)
Location: block/blk-mq.c:202
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_start_queue
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff81430d00-ffffffff81430d40: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b3e0)
Location: block/blk-mq.c:241
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_start_queue
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff8145b3e0-ffffffff8145b420: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81492a8b)
Location: block/blk-mq.c:252
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - drivers/scsi/scsi_lib.c:scsi_start_queue
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff8148e850-ffffffff8148e87a: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ac98d)
Location: block/blk-mq.c:256
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814a81d0-ffffffff814a81fa: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814dac66)
Location: block/blk-mq.c:259
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814d6e20-ffffffff814d6e4c: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f4026)
Location: block/blk-mq.c:260
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814f01a0-ffffffff814f01cc: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8155465b)
Location: block/blk-mq.c:245
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff815504d0-ffffffff81550524: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81570d7f)
Location: block/blk-mq.c:249
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff8156c8f0-ffffffff8156c944: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81578cf2)
Location: block/blk-mq.c:249
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff81574470-ffffffff8157449e: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dde8b)
Location: block/blk-mq.c:256
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff815d8920-ffffffff815d894e: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81685130)
Location: block/blk-mq.c:294
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/genhd.c:del_gendisk
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff81685130-ffffffff816851db: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817430d0)
Location: block/blk-mq.c:298
Inline: False
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_unquiesce_tagset
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff817430d0-ffffffff8174317b: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177e710)
Location: block/blk-mq.c:257
Inline: True
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_unquiesce_tagset
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/virtio_blk.c:virtblk_restore
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff8177e710-ffffffff8177e7be: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c0db0)
Location: block/blk-mq.c:257
Inline: True
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_unquiesce_tagset
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff817c0db0-ffffffff817c0e55: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f38a8)
Location: block/blk-mq.c:260
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
  - drivers/mmc/core/queue.c:mmc_queue_resume
```
**Symbols:**

```
ffff8000105ef130-ffff8000105ef16c: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079f9d0)
Location: block/blk-mq.c:260
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev
  - drivers/md/dm-rq.c:dm_start_queue
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
  - drivers/mmc/core/queue.c:mmc_queue_resume
```
**Symbols:**

```
c079ba48-c079ba7c: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c00000000078b244)
Location: block/blk-mq.c:260
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
c000000000785d20-c000000000785d70: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000431e7c)
Location: block/blk-mq.c:260
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
  - drivers/mmc/core/queue.c:mmc_queue_resume
```
**Symbols:**

```
ffffffe00042e51a-ffffffe00042e552: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ec606)
Location: block/blk-mq.c:260
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/nvme/host/core.c:nvme_start_queues
  - drivers/nvme/host/core.c:nvme_kill_queues
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_dev_remove_admin
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814e8780-ffffffff814e87ac: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814dcb56)
Location: block/blk-mq.c:260
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/nvme/host/core.c:nvme_start_queues
  - drivers/nvme/host/core.c:nvme_kill_queues
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_dev_remove_admin
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814d8cf0-ffffffff814d8d1c: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8696)
Location: block/blk-mq.c:260
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814e4810-ffffffff814e483c: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81501636)
Location: block/blk-mq.c:260
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814fcc70-ffffffff814fcc9c: blk_mq_unquiesce_queue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
