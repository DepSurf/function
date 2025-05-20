# Function: <code>scsi_execute</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, int timeout, int retries, u64 flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815ad180)
Location: drivers/scsi/scsi_lib.c:216
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_execute_req_flags
  - drivers/scsi/scsi_lib.c:scsi_execute_req_flags
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
```
**Symbols:**

```
ffffffff815ad180-ffffffff815ad344: scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, int timeout, int retries, u64 flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816050c0)
Location: drivers/scsi/scsi_lib.c:182
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_execute_req_flags
  - drivers/scsi/scsi_lib.c:scsi_execute_req_flags
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff816050c0-ffffffff8160527e: scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, int timeout, int retries, u64 flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81635f60)
Location: drivers/scsi/scsi_lib.c:231
Inline: False
Direct callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff81635f60-ffffffff81635f9f: scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81649160)
Location: drivers/scsi/scsi_lib.c:237
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
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff81649160-ffffffff816493a7: scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b2380)
Location: drivers/scsi/scsi_lib.c:245
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
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff816b2380-ffffffff816b25c7: scsi_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_execute(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, unsigned char *sense, struct scsi_sense_hdr *sshdr, int timeout, int retries, u64 flags, req_flags_t rq_flags, int *resid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ee530)
Location: drivers/scsi/scsi_lib.c:258
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
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
**Symbols:**

```
ffffffff816ee530-ffffffff816ee788: scsi_execute (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scsi_sense_hdr *sshdr</code>
</li>
<li>
<b>Param added. </b>
<code>req_flags_t rq_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>sdev, cmd, data_direction, buffer, bufflen, sense, timeout, retries, flags, resid</code> ➡️ <code>sdev, cmd, data_direction, buffer, bufflen, sense, sshdr, timeout, retries, flags, rq_flags, resid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
