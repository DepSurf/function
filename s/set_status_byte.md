# Function: <code>set_status_byte</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81a2b479)
Location: include/scsi/scsi_cmnd.h:328
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81bae509)
Location: include/scsi/scsi_cmnd.h:329
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
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
In drivers/scsi/virtio_scsi.c (ffffffff81be238f)
Location: include/scsi/scsi_cmnd.h:334
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff81c05cde)
Location: include/scsi/scsi_cmnd.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81c0fe1e)
Location: include/scsi/scsi_cmnd.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_tf
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
In drivers/scsi/virtio_scsi.c (ffffffff81c374af)
Location: include/scsi/scsi_cmnd.h:334
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff81c59d0e)
Location: include/scsi/scsi_cmnd.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81c6505e)
Location: include/scsi/scsi_cmnd.h:334
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_tf
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
