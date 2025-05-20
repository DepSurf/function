# Function: <code>__scsi_execute</code>

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
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81635d90)
Location: drivers/scsi/scsi_lib.c:165
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_execute_req_flags
  - drivers/scsi/scsi_lib.c:scsi_execute_req_flags
  - drivers/scsi/scsi_lib.c:scsi_execute
```
**Symbols:**

```
ffffffff81635d90-ffffffff81635f55: __scsi_execute.isra.23 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817120d0)
Location: drivers/scsi/scsi_lib.c:250
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff817120d0-ffffffff81712328: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174da40)
Location: drivers/scsi/scsi_lib.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff8174da40-ffffffff8174dc9c: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81771bf0)
Location: drivers/scsi/scsi_lib.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff81771bf0-ffffffff81771e4c: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81834450)
Location: drivers/scsi/scsi_lib.c:241
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_get_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff81834450-ffffffff818346ac: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81844e30)
Location: drivers/scsi/scsi_lib.c:240
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_get_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff81844e30-ffffffff8184508f: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81827fc0)
Location: drivers/scsi/scsi_lib.c:206
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
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
ffffffff81827fc0-ffffffff8182821b: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b3900)
Location: drivers/scsi/scsi_lib.c:208
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
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
ffffffff818b3900-ffffffff818b3b55: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a00710)
Location: drivers/scsi/scsi_lib.c:209
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_get_vpd_size
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
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
ffffffff81a00710-ffffffff81a0098f: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, blk_opf_t flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:207
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_get_vpd_size
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
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
ffffffff8209ba7f-ffffffff8209baa2: __scsi_execute.cold (STB_LOCAL)
ffffffff81b7ed40-ffffffff81b7f01d: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010975420)
Location: drivers/scsi/scsi_lib.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffff800010975420-ffff8000109755f8: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a499a8)
Location: drivers/scsi/scsi_lib.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
c0a499a8-c0a49b44: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a2f120)
Location: drivers/scsi/scsi_lib.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
c000000000a2f120-c000000000a2f374: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005dda70)
Location: drivers/scsi/scsi_lib.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffe0005dda70-ffffffe0005ddbdc: __scsi_execute (STB_GLOBAL)
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
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817262e0)
Location: drivers/scsi/scsi_lib.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff817262e0-ffffffff8172653c: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ff710)
Location: drivers/scsi/scsi_lib.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff816ff710-ffffffff816ff96c: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817650b0)
Location: drivers/scsi/scsi_lib.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff817650b0-ffffffff8176530c: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81780740)
Location: drivers/scsi/scsi_lib.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_sec_submit
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff81780740-ffffffff8178099c: __scsi_execute (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u64 flags</code> ➡️ <code>blk_opf_t flags</code>
</li>
</ul>
</details>
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
