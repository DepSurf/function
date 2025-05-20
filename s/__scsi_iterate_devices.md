# Function: <code>__scsi_iterate_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a6800)
Location: drivers/scsi/scsi.c:945
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff815a6800-ffffffff815a68b8: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815fea90)
Location: drivers/scsi/scsi.c:960
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff815fea90-ffffffff815feb48: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162e0e0)
Location: drivers/scsi/scsi.c:963
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff8162e0e0-ffffffff8162e198: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81643500)
Location: drivers/scsi/scsi.c:604
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff81643500-ffffffff81643581: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ac610)
Location: drivers/scsi/scsi.c:584
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff816ac610-ffffffff816ac691: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e8b40)
Location: drivers/scsi/scsi.c:584
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff816e8b40-ffffffff816e8bc1: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170c640)
Location: drivers/scsi/scsi.c:584
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff8170c640-ffffffff8170c6c1: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747d60)
Location: drivers/scsi/scsi.c:564
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff81747d60-ffffffff81747de0: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176beb0)
Location: drivers/scsi/scsi.c:564
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff8176beb0-ffffffff8176bf30: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182e763)
Location: drivers/scsi/scsi.c:554
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:starget_for_each_device
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff8182e140-ffffffff8182e1d7: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183f7a3)
Location: drivers/scsi/scsi.c:554
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:starget_for_each_device
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff8183f180-ffffffff8183f217: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81822a03)
Location: drivers/scsi/scsi.c:567
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:starget_for_each_device
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff81822390-ffffffff81822428: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818ad343)
Location: drivers/scsi/scsi.c:564
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:starget_for_each_device
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff818accd0-ffffffff818acd6b: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f7d82)
Location: drivers/scsi/scsi.c:597
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:starget_for_each_device
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff819f7a30-ffffffff819f7ad4: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b75682)
Location: drivers/scsi/scsi.c:597
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:starget_for_each_device
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff81b752f0-ffffffff81b75394: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc8fb2)
Location: drivers/scsi/scsi.c:753
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:starget_for_each_device
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/virtio_scsi.c:virtscsi_rescan_hotunplug
```
**Symbols:**

```
ffffffff81bc8c20-ffffffff81bc8cc4: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1dea2)
Location: drivers/scsi/scsi.c:782
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:starget_for_each_device
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/virtio_scsi.c:virtscsi_rescan_hotunplug
```
**Symbols:**

```
ffffffff81c1db10-ffffffff81c1dbb4: __scsi_iterate_devices (STB_GLOBAL)
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
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096e4c8)
Location: drivers/scsi/scsi.c:564
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffff80001096e4c8-ffff80001096e5c8: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a43930)
Location: drivers/scsi/scsi.c:564
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
c0a43930-c0a439c0: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a27440)
Location: drivers/scsi/scsi.c:564
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport
```
**Symbols:**

```
c000000000a27440-c000000000a27538: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d871a)
Location: drivers/scsi/scsi.c:564
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffe0005d871a-ffffffe0005d87ac: __scsi_iterate_devices (STB_GLOBAL)
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
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff817205a0)
Location: drivers/scsi/scsi.c:564
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff817205a0-ffffffff81720620: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f99d0)
Location: drivers/scsi/scsi.c:564
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/storvsc_drv.c:storvsc_host_scan
  - drivers/scsi/storvsc_drv.c:storvsc_host_scan
```
**Symbols:**

```
ffffffff816f99d0-ffffffff816f9a50: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175f370)
Location: drivers/scsi/scsi.c:564
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
```
**Symbols:**

```
ffffffff8175f370-ffffffff8175f3f0: __scsi_iterate_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct scsi_device *__scsi_iterate_devices(struct Scsi_Host *shost, struct scsi_device *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177a9d0)
Location: drivers/scsi/scsi.c:564
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_full
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_error.c:scsi_handle_queue_ramp_up
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff8177a9d0-ffffffff8177aa50: __scsi_iterate_devices (STB_GLOBAL)
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
