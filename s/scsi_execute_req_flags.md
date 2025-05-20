# Function: <code>scsi_execute_req_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_execute_req_flags(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, struct scsi_sense_hdr *sshdr, int timeout, int retries, int *resid, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815aee70)
Location: drivers/scsi/scsi_lib.c:266
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff815aee70-ffffffff815aef5e: scsi_execute_req_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_execute_req_flags(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, struct scsi_sense_hdr *sshdr, int timeout, int retries, int *resid, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81607100)
Location: drivers/scsi/scsi_lib.c:232
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
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
```
**Symbols:**

```
ffffffff81607100-ffffffff816071f4: scsi_execute_req_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_execute_req_flags(struct scsi_device *sdev, const unsigned char *cmd, int data_direction, void *buffer, unsigned int bufflen, struct scsi_sense_hdr *sshdr, int timeout, int retries, int *resid, u64 flags, req_flags_t rq_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816367b0)
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
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/sd.c:sd_start_stop_device
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sync_cache
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
```
**Symbols:**

```
ffffffff816367b0-ffffffff816368ba: scsi_execute_req_flags (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>req_flags_t rq_flags</code>
</li>
</ul>
</details>
</li>
</ul>
