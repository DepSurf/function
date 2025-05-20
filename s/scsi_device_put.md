# Function: <code>scsi_device_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a67d0)
Location: drivers/scsi/scsi.c:937
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
```
**Symbols:**

```
ffffffff815a67d0-ffffffff815a67fe: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815fea60)
Location: drivers/scsi/scsi.c:952
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff815fea60-ffffffff815fea8e: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162e0b0)
Location: drivers/scsi/scsi.c:955
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff8162e0b0-ffffffff8162e0de: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816434d0)
Location: drivers/scsi/scsi.c:596
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff816434d0-ffffffff816434fe: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ac5e0)
Location: drivers/scsi/scsi.c:576
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff816ac5e0-ffffffff816ac60e: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e8b10)
Location: drivers/scsi/scsi.c:576
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff816e8b10-ffffffff816e8b3e: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170c610)
Location: drivers/scsi/scsi.c:576
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff8170c610-ffffffff8170c63e: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747d30)
Location: drivers/scsi/scsi.c:556
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff81747d30-ffffffff81747d5e: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176be80)
Location: drivers/scsi/scsi.c:556
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff8176be80-ffffffff8176beae: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182e040)
Location: drivers/scsi/scsi.c:546
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_remove_dev
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff8182e040-ffffffff8182e071: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183f080)
Location: drivers/scsi/scsi.c:546
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_remove_dev
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff8183f080-ffffffff8183f0b1: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81822290)
Location: drivers/scsi/scsi.c:559
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff81822290-ffffffff818222c2: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818acbd0)
Location: drivers/scsi/scsi.c:554
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff818acbd0-ffffffff818acc07: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f7790)
Location: drivers/scsi/scsi.c:587
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sr.c:sr_block_release
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff819f7790-ffffffff819f77ce: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b745a0)
Location: drivers/scsi/scsi.c:587
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sr.c:sr_block_release
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff81b745a0-ffffffff81b745de: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc7d80)
Location: drivers/scsi/scsi.c:743
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sr.c:sr_block_release
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff81bc7d80-ffffffff81bc7dbe: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1c8f0)
Location: drivers/scsi/scsi.c:772
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sr.c:sr_block_release
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff81c1c8f0-ffffffff81c1c92e: scsi_device_put (STB_GLOBAL)
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
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096ddd8)
Location: drivers/scsi/scsi.c:556
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffff80001096ddd8-ffff80001096de14: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a438fc)
Location: drivers/scsi/scsi.c:556
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
c0a438fc-c0a43930: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a273e0)
Location: drivers/scsi/scsi.c:556
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
c000000000a273e0-c000000000a27438: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d86e0)
Location: drivers/scsi/scsi.c:556
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffe0005d86e0-ffffffe0005d871a: scsi_device_put (STB_GLOBAL)
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
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81720570)
Location: drivers/scsi/scsi.c:556
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff81720570-ffffffff8172059e: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f99a0)
Location: drivers/scsi/scsi.c:556
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/storvsc_drv.c:storvsc_remove_lun
  - drivers/scsi/storvsc_drv.c:storvsc_device_scan
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff816f99a0-ffffffff816f99ce: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175f340)
Location: drivers/scsi/scsi.c:556
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff8175f340-ffffffff8175f36e: scsi_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_device_put(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177a9a0)
Location: drivers/scsi/scsi.c:556
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:scsi_disk_put
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
**Symbols:**

```
ffffffff8177a9a0-ffffffff8177a9ce: scsi_device_put (STB_GLOBAL)
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
