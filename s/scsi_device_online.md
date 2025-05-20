# Function: <code>scsi_device_online</code>

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
In drivers/scsi/scsi_error.c (ffffffff815aba55)
Location: include/scsi/scsi_device.h:447
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_device.h:447
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/scsi/scsi_device.h:447
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/scsi/scsi_device.h:447
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/scsi/scsi_device.h:447
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff816047fc)
Location: include/scsi/scsi_device.h:460
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff816084dd)
Location: include/scsi/scsi_device.h:460
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/sd.c (ffffffff816154d9)
Location: include/scsi/scsi_device.h:460
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81618632)
Location: include/scsi/scsi_device.h:460
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff8161c6b9)
Location: include/scsi/scsi_device.h:460
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff81633ede)
Location: include/scsi/scsi_device.h:461
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81637dcd)
Location: include/scsi/scsi_device.h:461
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/sd.c (ffffffff81644ef9)
Location: include/scsi/scsi_device.h:461
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff816492b2)
Location: include/scsi/scsi_device.h:461
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff8164d2ca)
Location: include/scsi/scsi_device.h:461
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff81648b2a)
Location: include/scsi/scsi_device.h:460
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164bbf2)
Location: include/scsi/scsi_device.h:460
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/sd.c (ffffffff81658717)
Location: include/scsi/scsi_device.h:460
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8165dbdb)
Location: include/scsi/scsi_device.h:460
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff81660edf)
Location: include/scsi/scsi_device.h:460
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff816b1c34)
Location: include/scsi/scsi_device.h:476
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b50d1)
Location: include/scsi/scsi_device.h:476
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/sd.c (ffffffff816c1d57)
Location: include/scsi/scsi_device.h:476
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff816c71c3)
Location: include/scsi/scsi_device.h:476
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff816ca03f)
Location: include/scsi/scsi_device.h:476
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff816edf51)
Location: include/scsi/scsi_device.h:476
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f113a)
Location: include/scsi/scsi_device.h:476
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/sd.c (ffffffff816fe3b9)
Location: include/scsi/scsi_device.h:476
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81703a53)
Location: include/scsi/scsi_device.h:476
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff817068ac)
Location: include/scsi/scsi_device.h:476
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff81711b3c)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/sd.c (ffffffff81720f99)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81725fc9)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff817293ec)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff8174cff1)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750b8a)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff8175c665)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff817616fb)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff817646fc)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff81771171)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774dd5)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81780535)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff817856eb)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff817886ec)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff818333b7)
Location: include/scsi/scsi_device.h:497
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81837e37)
Location: include/scsi/scsi_device.h:497
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff818466ff)
Location: include/scsi/scsi_device.h:497
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81849995)
Location: include/scsi/scsi_device.h:497
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff8184cff6)
Location: include/scsi/scsi_device.h:497
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff81843fb6)
Location: include/scsi/scsi_device.h:498
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff818487b4)
Location: include/scsi/scsi_device.h:498
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81858253)
Location: include/scsi/scsi_device.h:498
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81859ef2)
Location: include/scsi/scsi_device.h:498
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff8185d4a6)
Location: include/scsi/scsi_device.h:498
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff8182712b)
Location: include/scsi/scsi_device.h:499
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bb39)
Location: include/scsi/scsi_device.h:499
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff8183b1d3)
Location: include/scsi/scsi_device.h:499
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8183cf02)
Location: include/scsi/scsi_device.h:499
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff8184031a)
Location: include/scsi/scsi_device.h:499
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff818b2afb)
Location: include/scsi/scsi_device.h:506
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b76ec)
Location: include/scsi/scsi_device.h:506
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff818c78b3)
Location: include/scsi/scsi_device.h:506
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff818c988b)
Location: include/scsi/scsi_device.h:506
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff818ccc1a)
Location: include/scsi/scsi_device.h:506
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff819fdd15)
Location: include/scsi/scsi_device.h:514
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02dde)
Location: include/scsi/scsi_device.h:514
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81a14426)
Location: include/scsi/scsi_device.h:514
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81a16c01)
Location: include/scsi/scsi_device.h:514
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff81a1a73c)
Location: include/scsi/scsi_device.h:514
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff81b7c165)
Location: include/scsi/scsi_device.h:515
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81819)
Location: include/scsi/scsi_device.h:515
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81b94836)
Location: include/scsi/scsi_device.h:515
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81b97a61)
Location: include/scsi/scsi_device.h:515
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff81b9b8cc)
Location: include/scsi/scsi_device.h:515
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff81bcfeb5)
Location: include/scsi/scsi_device.h:517
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd551f)
Location: include/scsi/scsi_device.h:517
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81beadb2)
Location: include/scsi/scsi_device.h:517
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81bedfe0)
Location: include/scsi/scsi_device.h:517
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff81bf1ebc)
Location: include/scsi/scsi_device.h:517
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff81c24b15)
Location: include/scsi/scsi_device.h:538
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a177)
Location: include/scsi/scsi_device.h:538
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81c40415)
Location: include/scsi/scsi_device.h:538
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81c436ed)
Location: include/scsi/scsi_device.h:538
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff81c477ac)
Location: include/scsi/scsi_device.h:538
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffff800010974624)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffff800010978d18)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffff800010986c30)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffff80001098bfd4)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffff80001098fee8)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (c0a4905c)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (c0a4cb2c)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (c0a58f2c)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (c0a5e340)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (c0a61fcc)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (c000000000a2e5c0)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (c000000000a332e0)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (c000000000a461d4)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (c000000000a4ce00)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (c000000000a51bc0)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffe0005dd1dc)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0634)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffe0005eb14a)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffe0005f063c)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffe0005f3cd4)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff81725861)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff817294c5)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81734c25)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff81739ddb)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff8173cddc)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff816fec91)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff817028e3)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff817168c5)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8171ba7b)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff8171ea7c)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff81764631)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81768295)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff817753b5)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8177a56b)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff8177d56c)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
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
In drivers/scsi/scsi_error.c (ffffffff8177fcb1)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff817839bc)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff8178f195)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sr.c (ffffffff8179439b)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (ffffffff8179738c)
Location: include/scsi/scsi_device.h:488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
</details>
</li>
</ul>

## Differences
