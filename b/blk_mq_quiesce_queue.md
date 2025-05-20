# Function: <code>blk_mq_quiesce_queue</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814212d0)
Location: block/blk-mq.c:128
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff814212d0-ffffffff8142137a: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142efe0)
Location: block/blk-mq.c:176
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff8142efe0-ffffffff8142f064: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145a470)
Location: block/blk-mq.c:215
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff8145a470-ffffffff8145a4f4: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148db00)
Location: block/blk-mq.c:226
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff8148db00-ffffffff8148db8c: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7390)
Location: block/blk-mq.c:230
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff814a7390-ffffffff814a7410: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5330)
Location: block/blk-mq.c:233
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff814d5330-ffffffff814d53b0: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee610)
Location: block/blk-mq.c:234
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff814ee610-ffffffff814ee690: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154e280)
Location: block/blk-mq.c:219
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff8154e280-ffffffff8154e300: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156a710)
Location: block/blk-mq.c:223
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff8156a710-ffffffff8156a790: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81572650)
Location: block/blk-mq.c:223
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff81572650-ffffffff815726d0: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d6c80)
Location: block/blk-mq.c:230
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff815d6c80-ffffffff815d6d00: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168bb5c)
Location: block/blk-mq.c:280
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/genhd.c:del_gendisk
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff816859d0-ffffffff81685a5c: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8174a23c)
Location: block/blk-mq.c:282
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff817437c0-ffffffff81743858: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8178693f)
Location: block/blk-mq.c:241
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/virtio_blk.c:virtblk_freeze
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff8177ef30-ffffffff8177efcb: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c901c)
Location: block/blk-mq.c:241
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff817c1cf0-ffffffff817c1d82: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ed2b0)
Location: block/blk-mq.c:234
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
  - drivers/mmc/core/queue.c:mmc_queue_suspend
```
**Symbols:**

```
ffff8000105ed2b0-ffff8000105ed34c: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c07997c0)
Location: block/blk-mq.c:234
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev
  - drivers/md/dm-rq.c:dm_stop_queue
  - drivers/mmc/core/queue.c:mmc_queue_suspend
```
**Symbols:**

```
c07997c0-c0799848: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000783000)
Location: block/blk-mq.c:234
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
c000000000783000-c0000000007830f4: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042cc3a)
Location: block/blk-mq.c:234
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
  - drivers/mmc/core/queue.c:mmc_queue_suspend
```
**Symbols:**

```
ffffffe00042cc3a-ffffffe00042ccd4: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6bf0)
Location: block/blk-mq.c:234
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/nvme/host/core.c:nvme_stop_queues
  - drivers/nvme/host/pci.c:nvme_suspend_queue
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff814e6bf0-ffffffff814e6c70: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7160)
Location: block/blk-mq.c:234
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/nvme/host/core.c:nvme_stop_queues
  - drivers/nvme/host/pci.c:nvme_suspend_queue
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff814d7160-ffffffff814d71e0: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e2c80)
Location: block/blk-mq.c:234
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff814e2c80-ffffffff814e2d00: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_quiesce_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fbb00)
Location: block/blk-mq.c:234
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff814fbb00-ffffffff814fbb80: blk_mq_quiesce_queue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
