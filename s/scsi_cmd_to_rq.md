# Function: <code>scsi_cmd_to_rq</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_cmnd.h:146
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/scsi/scsi_cmnd.h:146
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b535b)
Location: include/scsi/scsi_cmnd.h:146
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/scsi/scsi_cmnd.h:146
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/scsi/scsi_cmnd.h:146
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8db4)
Location: include/scsi/scsi_cmnd.h:146
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sr.c (ffffffff818c9844)
Location: include/scsi/scsi_cmnd.h:146
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/scsi/scsi_cmnd.h:146
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff818e1ca8)
Location: include/scsi/scsi_cmnd.h:146
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_cmnd.h:141
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/scsi/scsi_cmnd.h:141
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a01f95)
Location: include/scsi/scsi_cmnd.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/scsi/scsi_cmnd.h:141
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/scsi/scsi_cmnd.h:141
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a16324)
Location: include/scsi/scsi_cmnd.h:141
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sr.c (ffffffff81a16bb5)
Location: include/scsi/scsi_cmnd.h:141
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/scsi/scsi_cmnd.h:141
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff81a32cd8)
Location: include/scsi/scsi_cmnd.h:141
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_cmnd.h:142
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/scsi/scsi_cmnd.h:142
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b80655)
Location: include/scsi/scsi_cmnd.h:142
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/scsi/scsi_cmnd.h:142
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/scsi/scsi_cmnd.h:142
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b97104)
Location: include/scsi/scsi_cmnd.h:142
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sr.c (ffffffff81b97a15)
Location: include/scsi/scsi_cmnd.h:142
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/scsi/scsi_cmnd.h:142
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff81bb73e8)
Location: include/scsi/scsi_cmnd.h:142
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd46d5)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be26e5)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/scsi/sd.c (ffffffff81be83c9)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bed6a4)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sr.c (ffffffff81bedf95)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff81c0e9f8)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c29345)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c378c5)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/scsi/sd.c (ffffffff81c3d936)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c42d85)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sr.c (ffffffff81c436a5)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff81c63baa)
Location: include/scsi/scsi_cmnd.h:147
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
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
