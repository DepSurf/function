# Function: <code>scsi_device_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a66c0)
Location: drivers/scsi/scsi.c:912
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
```
**Symbols:**

```
ffffffff815a66c0-ffffffff815a6723: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815fe950)
Location: drivers/scsi/scsi.c:927
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff815fe950-ffffffff815fe9b3: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162dfa0)
Location: drivers/scsi/scsi.c:930
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff8162dfa0-ffffffff8162e003: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816433b0)
Location: drivers/scsi/scsi.c:571
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff816433b0-ffffffff81643413: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ac4c0)
Location: drivers/scsi/scsi.c:551
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff816ac4c0-ffffffff816ac523: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e89f0)
Location: drivers/scsi/scsi.c:551
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff816e89f0-ffffffff816e8a53: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170c4f0)
Location: drivers/scsi/scsi.c:551
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff8170c4f0-ffffffff8170c553: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747c10)
Location: drivers/scsi/scsi.c:531
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff81747c10-ffffffff81747c73: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176bd60)
Location: drivers/scsi/scsi.c:531
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff8176bd60-ffffffff8176bdc3: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182dfd0)
Location: drivers/scsi/scsi.c:521
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_remove_dev
```
**Symbols:**

```
ffffffff8182dfd0-ffffffff8182e033: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183f010)
Location: drivers/scsi/scsi.c:521
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_remove_dev
```
**Symbols:**

```
ffffffff8183f010-ffffffff8183f073: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81822220)
Location: drivers/scsi/scsi.c:534
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff81822220-ffffffff81822284: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818acb60)
Location: drivers/scsi/scsi.c:529
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff818acb60-ffffffff818acbc4: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f7720)
Location: drivers/scsi/scsi.c:562
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff819f7720-ffffffff819f7790: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b74510)
Location: drivers/scsi/scsi.c:562
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff81b74510-ffffffff81b74587: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc7cf0)
Location: drivers/scsi/scsi.c:718
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff81bc7cf0-ffffffff81bc7d67: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1c860)
Location: drivers/scsi/scsi.c:747
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:starget_for_each_device
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff81c1c860-ffffffff81c1c8d7: scsi_device_get (STB_GLOBAL)
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
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096dd68)
Location: drivers/scsi/scsi.c:531
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffff80001096dd68-ffff80001096ddd8: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a437d4)
Location: drivers/scsi/scsi.c:531
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sd.c:scsi_disk_get
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
c0a437d4-c0a43840: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a271e0)
Location: drivers/scsi/scsi.c:531
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sd.c:scsi_disk_get
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
c000000000a271e0-c000000000a2728c: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d85dc)
Location: drivers/scsi/scsi.c:531
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sd.c:scsi_disk_get
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffe0005d85dc-ffffffe0005d863e: scsi_device_get (STB_GLOBAL)
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
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81720450)
Location: drivers/scsi/scsi.c:531
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff81720450-ffffffff817204b3: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f9880)
Location: drivers/scsi/scsi.c:531
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff816f9880-ffffffff816f98e3: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175f220)
Location: drivers/scsi/scsi.c:531
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff8175f220-ffffffff8175f283: scsi_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_device_get(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177a880)
Location: drivers/scsi/scsi.c:531
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
```
**Symbols:**

```
ffffffff8177a880-ffffffff8177a8e3: scsi_device_get (STB_GLOBAL)
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
