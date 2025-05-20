# Function: <code>scsi_status_is_check_condition</code>

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
In drivers/scsi/scsi.c (ffffffff818ad497)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_log_completion
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/scsi/scsi.h:74
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff818b27e5)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b59b7)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b8e32)
Location: include/scsi/scsi.h:74
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (ffffffff818c0c10)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff818c5ba0)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_sync_cache
```
```
In drivers/scsi/sr.c (ffffffff818c971c)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/scsi/sr_ioctl.c (ffffffff818cae9b)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
```
```
In drivers/ata/libata-scsi.c (ffffffff818dd687)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
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
In drivers/scsi/scsi.c (ffffffff819f8178)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_log_completion
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/scsi/scsi.h:74
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff819fd975)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a00d77)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a0472a)
Location: include/scsi/scsi.h:74
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (ffffffff81a0d322)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff81a125b5)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_sync_cache
```
```
In drivers/scsi/sr.c (ffffffff81a16a75)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81a1801b)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2e749)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
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
In drivers/scsi/scsi.c (ffffffff81b75b38)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_log_completion
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/scsi/scsi.h:74
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7bda5)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7f1d7)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b8334a)
Location: include/scsi/scsi.h:74
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (ffffffff81b8d172)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff81b928a0)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_sync_cache
```
```
In drivers/scsi/sr.c (ffffffff81b978c5)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81b98f4b)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb1bb9)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
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
In drivers/scsi/scsi.c (ffffffff81bc9458)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_log_completion
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/scsi/scsi.h:74
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcfab9)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd3324)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd709a)
Location: include/scsi/scsi.h:74
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (ffffffff81be1183)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff81be8c8d)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_sync_cache
```
```
In drivers/scsi/sr.c (ffffffff81bede6a)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81bef4fe)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
```
```
In drivers/ata/libata-scsi.c (ffffffff81c090b0)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
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
In drivers/scsi/scsi.c (ffffffff81c1e048)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_log_completion
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/scsi/scsi.h:74
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81c24719)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_noretry_cmd
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c27fa4)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2bd3d)
Location: include/scsi/scsi.h:74
Inline: True
```
```
In drivers/scsi/scsi_bsg.c (ffffffff81c361b3)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sd.c (ffffffff81c3e1d2)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_sync_cache
```
```
In drivers/scsi/sr.c (ffffffff81c4357a)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81c44c9e)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5e190)
Location: include/scsi/scsi.h:74
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
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
