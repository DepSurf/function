# Function: <code>blk_mq_freeze_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c4ee0)
Location: block/blk-mq.c:115
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_switch
```
**Symbols:**

```
ffffffff813c4ee0-ffffffff813c4efd: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8140965e)
Location: block/blk-mq.c:115
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_switch
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
**Symbols:**

```
ffffffff814090b0-ffffffff814090cd: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142405e)
Location: block/blk-mq.c:97
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
**Symbols:**

```
ffffffff81423a70-ffffffff81423a8d: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8143304d)
Location: block/blk-mq.c:130
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_switch
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
```
**Symbols:**

```
ffffffff81430c70-ffffffff81430c8d: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145ec08)
Location: block/blk-mq.c:169
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff8145c670-ffffffff8145c680: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81492557)
Location: block/blk-mq.c:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff8148ffa0-ffffffff8148ffb0: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ac112)
Location: block/blk-mq.c:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff814a82b0-ffffffff814a82cd: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814da348)
Location: block/blk-mq.c:191
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff814d6d60-ffffffff814d6d7f: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f3708)
Location: block/blk-mq.c:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff814f00e0-ffffffff814f00ff: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81553c8a)
Location: block/blk-mq.c:177
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff815505c0-ffffffff815505e1: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8157034a)
Location: block/blk-mq.c:181
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_shared
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff8156c9e0-ffffffff8156ca01: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815782aa)
Location: block/blk-mq.c:181
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_shared
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-zoned.c:blk_queue_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-wbt.c:wbt_init
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff815743a0-ffffffff815743c1: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dd38a)
Location: block/blk-mq.c:181
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-ioprio.c:blk_ioprio_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-zoned.c:blk_queue_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-wbt.c:wbt_init
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff815d88f0-ffffffff815d8911: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168af37)
Location: block/blk-mq.c:210
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-ioprio.c:blk_ioprio_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-zoned.c:blk_queue_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-wbt.c:wbt_init
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff81685100-ffffffff81685126: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81748ed7)
Location: block/blk-mq.c:210
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-zoned.c:disk_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-wbt.c:wbt_init
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff81743090-ffffffff817430b6: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817855f7)
Location: block/blk-mq.c:169
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-rq-qos.c:rq_qos_del
  - block/blk-rq-qos.c:rq_qos_add
  - block/blk-cgroup.c:blkcg_deactivate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-zoned.c:disk_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff8177e6d0-ffffffff8177e6f6: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c7c3d)
Location: block/blk-mq.c:169
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-rq-qos.c:rq_qos_del
  - block/blk-rq-qos.c:rq_qos_add
  - block/blk-cgroup.c:blkcg_deactivate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/virtio_blk.c:virtblk_freeze
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff817c0d70-ffffffff817c0d96: blk_mq_freeze_queue (STB_GLOBAL)
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
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f2f60)
Location: block/blk-mq.c:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffff8000105ef050-ffff8000105ef084: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079f054)
Location: block/blk-mq.c:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev
```
**Symbols:**

```
c079b984-c079b9ac: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c00000000078a600)
Location: block/blk-mq.c:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
c000000000785bd0-c000000000785c10: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000431724)
Location: block/blk-mq.c:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffe00042e450-ffffffe00042e484: blk_mq_freeze_queue (STB_GLOBAL)
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
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ebce8)
Location: block/blk-mq.c:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814e86c0-ffffffff814e86df: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814dc238)
Location: block/blk-mq.c:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814d8c30-ffffffff814d8c4f: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7d78)
Location: block/blk-mq.c:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff814e4750-ffffffff814e476f: blk_mq_freeze_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_freeze_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81500d18)
Location: block/blk-mq.c:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
  - block/blk-sysfs.c:queue_wb_lat_store
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/sd.c:scsi_disk_release
```
**Symbols:**

```
ffffffff814fcbb0-ffffffff814fcbcf: blk_mq_freeze_queue (STB_GLOBAL)
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
