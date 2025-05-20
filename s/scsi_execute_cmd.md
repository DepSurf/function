# Function: <code>scsi_execute_cmd</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int scsi_execute_cmd(struct scsi_device *sdev, const unsigned char *cmd, blk_opf_t opf, void *buffer, unsigned int bufflen, int timeout, int retries, const struct scsi_exec_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:201
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_get_vpd_size
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/virtio_scsi.c:virtscsi_rescan_hotunplug
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff8211c916-ffffffff8211c939: scsi_execute_cmd.cold (STB_LOCAL)
ffffffff81bd2cd0-ffffffff81bd2fb3: scsi_execute_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int scsi_execute_cmd(struct scsi_device *sdev, const unsigned char *cmd, blk_opf_t opf, void *buffer, unsigned int bufflen, int timeout, int retries, const struct scsi_exec_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:201
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/virtio_scsi.c:virtscsi_rescan_hotunplug
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff821fa7c6-ffffffff821fa7e9: scsi_execute_cmd.cold (STB_LOCAL)
ffffffff81c27940-ffffffff81c27c23: scsi_execute_cmd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
