# Function: <code>scsi_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.h:100
Inline: True
```
```
In drivers/scsi/sd_dif.c (0)
Location: drivers/scsi/sd.h:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.h:100
Inline: True
```
```
In drivers/scsi/sd_dif.c (0)
Location: drivers/scsi/sd.h:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.h:112
Inline: True
```
```
In drivers/scsi/sd_dif.c (0)
Location: drivers/scsi/sd.h:112
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd.h:112
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.h:123
Inline: True
```
```
In drivers/scsi/sd_dif.c (0)
Location: drivers/scsi/sd.h:123
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd.h:123
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.h:124
Inline: True
```
```
In drivers/scsi/sd_dif.c (0)
Location: drivers/scsi/sd.h:124
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd.h:124
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816fc005)
Location: drivers/scsi/sd.h:123
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff8170248c)
Location: drivers/scsi/sd.h:123
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sd_zbc.c (ffffffff81702cb3)
Location: drivers/scsi/sd.h:123
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8171edd5)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81725683)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175a4c5)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81760ce3)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8177e3d5)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81784c83)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81841985)
Location: drivers/scsi/sd.h:128
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff818483b5)
Location: drivers/scsi/sd.h:128
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones_cb
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81851ea5)
Location: drivers/scsi/sd.h:131
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81858905)
Location: drivers/scsi/sd.h:131
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones_cb
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81834f35)
Location: drivers/scsi/sd.h:131
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183b885)
Location: drivers/scsi/sd.h:131
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones_cb
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c1285)
Location: drivers/scsi/sd.h:131
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8095)
Location: drivers/scsi/sd.h:131
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones_cb
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (ffffffff81a0d9d5)
Location: drivers/scsi/sd.h:156
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:scsi_disk_free_disk
  - drivers/scsi/sd.c:sd_get_unique_id
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a14eb5)
Location: drivers/scsi/sd.h:156
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones_cb
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (ffffffff81b8d8f5)
Location: drivers/scsi/sd.h:156
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:scsi_disk_free_disk
  - drivers/scsi/sd.c:sd_get_unique_id
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b95475)
Location: drivers/scsi/sd.h:156
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones_cb
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (ffffffff81be3985)
Location: drivers/scsi/sd.h:156
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:scsi_disk_free_disk
  - drivers/scsi/sd.c:sd_pr_read_reservation
  - drivers/scsi/sd.c:sd_get_unique_id
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81beba15)
Location: drivers/scsi/sd.h:156
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones_cb
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (ffffffff81c38c35)
Location: drivers/scsi/sd.h:157
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:scsi_disk_free_disk
  - drivers/scsi/sd.c:sd_pr_read_reservation
  - drivers/scsi/sd.c:sd_get_unique_id
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c410d5)
Location: drivers/scsi/sd.h:157
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones_cb
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff800010984b08)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffff80001098b8a0)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a57068)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:scsi_disk_get
```
```
In drivers/scsi/sd_zbc.c (c0a5dbe0)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a43630)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:scsi_disk_get
```
```
In drivers/scsi/sd_zbc.c (c000000000a4c58c)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005e987c)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:scsi_disk_get
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005efe7a)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81732ac5)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81739373)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81714765)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171b013)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81773255)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81779b03)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8178d035)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_unlock_native_capacity
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_eh_action
  - drivers/scsi/sd.c:sd_eh_reset
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81793933)
Location: drivers/scsi/sd.h:122
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
</ul>

## Differences
