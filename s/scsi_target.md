# Function: <code>scsi_target</code>

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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_device.h:290
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/scsi/scsi_device.h:290
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_device.h:290
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/scsi/scsi_device.h:290
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/scsi/scsi_device.h:290
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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_device.h:299
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81601c73)
Location: include/scsi/scsi_device.h:299
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_device.h:299
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/scsi/scsi_device.h:299
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8160e30a)
Location: include/scsi/scsi_device.h:299
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_device.h:299
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81631363)
Location: include/scsi/scsi_device.h:299
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_device.h:299
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/scsi/scsi_device.h:299
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8163dbaa)
Location: include/scsi/scsi_device.h:299
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_device.h:301
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8164613e)
Location: include/scsi/scsi_device.h:301
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_device.h:301
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/scsi/scsi_device.h:301
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81652713)
Location: include/scsi/scsi_device.h:301
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_device.h:317
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816af12e)
Location: include/scsi/scsi_device.h:317
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_device.h:317
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/scsi/scsi_device.h:317
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816bbb0a)
Location: include/scsi/scsi_device.h:317
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff816e9306)
Location: include/scsi/scsi_device.h:317
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816eb4ca)
Location: include/scsi/scsi_device.h:317
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f24d9)
Location: include/scsi/scsi_device.h:317
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f4813)
Location: include/scsi/scsi_device.h:317
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816f7f5a)
Location: include/scsi/scsi_device.h:317
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff8170ce06)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8170ef7a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff81715029)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81716e4f)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8171a85a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff817484e5)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8174a70a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff8175080a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81751d59)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81755f2a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff8176c635)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8176e87a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774a2d)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81775fd9)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8177a1aa)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff8182e92a)
Location: include/scsi/scsi_device.h:328
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81830c5a)
Location: include/scsi/scsi_device.h:328
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff81837e69)
Location: include/scsi/scsi_device.h:328
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81838df1)
Location: include/scsi/scsi_device.h:328
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183d20d)
Location: include/scsi/scsi_device.h:328
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff8183f96a)
Location: include/scsi/scsi_device.h:329
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8184189a)
Location: include/scsi/scsi_device.h:329
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff8184881b)
Location: include/scsi/scsi_device.h:329
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81849671)
Location: include/scsi/scsi_device.h:329
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8184da0d)
Location: include/scsi/scsi_device.h:329
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff81822bca)
Location: include/scsi/scsi_device.h:330
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81824aaa)
Location: include/scsi/scsi_device.h:330
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bba9)
Location: include/scsi/scsi_device.h:330
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182ca8d)
Location: include/scsi/scsi_device.h:330
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81830ead)
Location: include/scsi/scsi_device.h:330
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff818ad50a)
Location: include/scsi/scsi_device.h:337
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff818b032a)
Location: include/scsi/scsi_device.h:337
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b775c)
Location: include/scsi/scsi_device.h:337
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b884d)
Location: include/scsi/scsi_device.h:337
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bceed)
Location: include/scsi/scsi_device.h:337
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff819f8206)
Location: include/scsi/scsi_device.h:346
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff819fb3c3)
Location: include/scsi/scsi_device.h:346
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02e4d)
Location: include/scsi/scsi_device.h:346
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a040fd)
Location: include/scsi/scsi_device.h:346
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a0909d)
Location: include/scsi/scsi_device.h:346
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff81b75bd6)
Location: include/scsi/scsi_device.h:347
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81b790d3)
Location: include/scsi/scsi_device.h:347
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81762)
Location: include/scsi/scsi_device.h:347
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b82ced)
Location: include/scsi/scsi_device.h:347
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b884c1)
Location: include/scsi/scsi_device.h:347
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff81bc94f6)
Location: include/scsi/scsi_device.h:353
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81bccd63)
Location: include/scsi/scsi_device.h:353
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd5465)
Location: include/scsi/scsi_device.h:353
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd69ed)
Location: include/scsi/scsi_device.h:353
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdc3a1)
Location: include/scsi/scsi_device.h:353
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff81c1e0e6)
Location: include/scsi/scsi_device.h:374
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81c21993)
Location: include/scsi/scsi_device.h:374
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a0c1)
Location: include/scsi/scsi_device.h:374
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2b644)
Location: include/scsi/scsi_device.h:374
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c310d1)
Location: include/scsi/scsi_device.h:374
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffff80001096ec44)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffff800010972098)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffff800010978ae8)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffff80001097a668)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097f88c)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (c0a440a4)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (c0a463ac)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (c0a4c980)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (c0a4e04c)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (c0a5268c)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (c000000000a28008)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (c000000000a2ae8c)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (c000000000a331d8)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (c000000000a34ff8)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (c000000000a3b3fc)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffe0005d8df2)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dad18)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0414)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e1814)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffe0005e5ac2)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff81720d25)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81722f6a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff8172911d)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172a6c9)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8172e89a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff816fa155)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816fc39a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff8170254d)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81703ae9)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81707cba)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170dd99)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_block_scsi_eh
  - drivers/scsi/scsi_transport_fc.c:fc_block_scsi_eh
  - drivers/scsi/scsi_transport_fc.c:fc_eh_timed_out
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
In drivers/scsi/scsi.c (ffffffff8175faf5)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81761d3a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767eed)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81769499)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8176d66a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
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
In drivers/scsi/scsi.c (ffffffff8177b155)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8177d39a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
```
```
In drivers/scsi/scsi_lib.c (ffffffff8178362c)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81784c09)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81788e0a)
Location: include/scsi/scsi_device.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
</details>
</li>
</ul>

## Differences
