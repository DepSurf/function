# Function: <code>blk_mq_unfreeze_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c3650)
Location: block/blk-mq.c:125
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_switch
```
**Symbols:**

```
ffffffff813c3650-ffffffff813c36b8: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81407120)
Location: block/blk-mq.c:125
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_switch
  - drivers/block/loop.c:__loop_update_dio
```
**Symbols:**

```
ffffffff81407120-ffffffff81407188: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814215b0)
Location: block/blk-mq.c:107
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_queue_reinit_work
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
```
**Symbols:**

```
ffffffff814215b0-ffffffff81421618: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142ff00)
Location: block/blk-mq.c:140
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_switch
  - drivers/block/loop.c:__loop_update_dio
```
**Symbols:**

```
ffffffff8142ff00-ffffffff8142ff4a: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b880)
Location: block/blk-mq.c:179
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff8145b880-ffffffff8145b8ca: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e320)
Location: block/blk-mq.c:194
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff8148e320-ffffffff8148e369: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7c90)
Location: block/blk-mq.c:198
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff814a7c90-ffffffff814a7cd9: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d52a0)
Location: block/blk-mq.c:201
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff814d52a0-ffffffff814d5306: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee580)
Location: block/blk-mq.c:202
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff814ee580-ffffffff814ee5e6: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154e1f0)
Location: block/blk-mq.c:187
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff8154e1f0-ffffffff8154e256: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156a680)
Location: block/blk-mq.c:191
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_shared
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff8156a680-ffffffff8156a6e3: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815725c0)
Location: block/blk-mq.c:191
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_shared
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-zoned.c:blk_queue_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-wbt.c:wbt_init
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff815725c0-ffffffff81572623: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dd5f1)
Location: block/blk-mq.c:205
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-ioprio.c:blk_ioprio_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-zoned.c:blk_queue_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-wbt.c:wbt_init
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff815d8c10-ffffffff815d8c73: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168b1d3)
Location: block/blk-mq.c:234
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-ioprio.c:blk_ioprio_init
  - block/blk-ioprio.c:blk_ioprio_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-zoned.c:blk_queue_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff81686170-ffffffff816861ef: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817491b0)
Location: block/blk-mq.c:234
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-zoned.c:disk_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff817442b0-ffffffff8174432f: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817857cb)
Location: block/blk-mq.c:193
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-rq-qos.c:rq_qos_del
  - block/blk-rq-qos.c:rq_qos_add
  - block/blk-rq-qos.c:rq_qos_add
  - block/blk-cgroup.c:blkcg_deactivate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-zoned.c:disk_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff8177fcd0-ffffffff8177fd4f: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c7e43)
Location: block/blk-mq.c:193
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-rq-qos.c:rq_qos_del
  - block/blk-rq-qos.c:rq_qos_add
  - block/blk-rq-qos.c:rq_qos_add
  - block/blk-cgroup.c:blkcg_deactivate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/virtio_blk.c:virtblk_restore
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff817c27b0-ffffffff817c282f: blk_mq_unfreeze_queue (STB_GLOBAL)
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
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ed1f8)
Location: block/blk-mq.c:202
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffff8000105ed1f8-ffff8000105ed280: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c07996f4)
Location: block/blk-mq.c:202
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev
```
**Symbols:**

```
c07996f4-c079979c: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000782ef0)
Location: block/blk-mq.c:202
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
c000000000782ef0-c000000000782fb8: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042cb98)
Location: block/blk-mq.c:202
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffe00042cb98-ffffffe00042cc0e: blk_mq_unfreeze_queue (STB_GLOBAL)
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
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6b60)
Location: block/blk-mq.c:202
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/nvme/host/core.c:nvme_unfreeze
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/nvme/host/multipath.c:nvme_mpath_unfreeze
```
**Symbols:**

```
ffffffff814e6b60-ffffffff814e6bc6: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d70d0)
Location: block/blk-mq.c:202
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/nvme/host/core.c:nvme_unfreeze
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/nvme/host/multipath.c:nvme_mpath_unfreeze
```
**Symbols:**

```
ffffffff814d70d0-ffffffff814d7136: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e2bf0)
Location: block/blk-mq.c:202
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff814e2bf0-ffffffff814e2c56: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_unfreeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fba70)
Location: block/blk-mq.c:202
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff814fba70-ffffffff814fbad6: blk_mq_unfreeze_queue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
