# Function: <code>ata_port_is_frozen</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba762e)
Location: include/linux/libata.h:1046
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81bae3ab)
Location: include/linux/libata.h:1046
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81bb65ec)
Location: include/linux/libata.h:1046
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_tf
  - drivers/ata/libata-eh.c:ata_eh_request_sense
```
```
In drivers/ata/libata-sata.c (ffffffff81bbeb48)
Location: include/linux/libata.h:1046
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
```
In drivers/ata/libata-acpi.c (ffffffff81bc797d)
Location: include/linux/libata.h:1046
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
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
In drivers/ata/libata-core.c (ffffffff81bfe1fa)
Location: include/linux/libata.h:1060
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81c05b5d)
Location: include/linux/libata.h:1060
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81c0d99c)
Location: include/linux/libata.h:1060
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_eh_analyze_tf
  - drivers/ata/libata-eh.c:ata_eh_request_sense
```
```
In drivers/ata/libata-sata.c (ffffffff81c167d8)
Location: include/linux/libata.h:1060
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
```
In drivers/ata/libata-acpi.c (ffffffff81c1f50d)
Location: include/linux/libata.h:1060
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
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
In drivers/ata/libata-core.c (ffffffff81c53f97)
Location: include/linux/libata.h:1059
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81c59b8d)
Location: include/linux/libata.h:1059
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81c62bf3)
Location: include/linux/libata.h:1059
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_eh_analyze_tf
  - drivers/ata/libata-eh.c:ata_eh_request_sense
```
```
In drivers/ata/libata-sata.c (ffffffff81c6b918)
Location: include/linux/libata.h:1059
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
```
In drivers/ata/libata-acpi.c (ffffffff81c7466d)
Location: include/linux/libata.h:1059
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
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
