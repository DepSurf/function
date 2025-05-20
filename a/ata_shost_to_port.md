# Function: <code>ata_shost_to_port</code>

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
In drivers/ata/libata-scsi.c (ffffffff815cfcd5)
Location: include/linux/libata.h:1733
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
```
```
In drivers/ata/libata-eh.c (ffffffff815d5917)
Location: include/linux/libata.h:1733
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
  - drivers/ata/libata-eh.c:ata_scsi_error
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
In drivers/ata/libata-scsi.c (ffffffff8162e0ce)
Location: include/linux/libata.h:1730
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff81633f89)
Location: include/linux/libata.h:1730
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
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
In drivers/ata/libata-scsi.c (ffffffff8165f21e)
Location: include/linux/libata.h:1736
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff816650d9)
Location: include/linux/libata.h:1736
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
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
In drivers/ata/libata-scsi.c (ffffffff81673c1e)
Location: include/linux/libata.h:1739
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff816798e9)
Location: include/linux/libata.h:1739
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
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
In drivers/ata/libata-scsi.c (ffffffff816dd20e)
Location: include/linux/libata.h:1740
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff816e2f49)
Location: include/linux/libata.h:1740
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
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
In drivers/ata/libata-scsi.c (ffffffff81719955)
Location: include/linux/libata.h:1767
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff8171f803)
Location: include/linux/libata.h:1767
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
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
In drivers/ata/libata-scsi.c (ffffffff8173c255)
Location: include/linux/libata.h:1766
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff817420f3)
Location: include/linux/libata.h:1766
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
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
In drivers/ata/libata-scsi.c (ffffffff81777d55)
Location: include/linux/libata.h:1751
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff8177dc63)
Location: include/linux/libata.h:1751
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
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
In drivers/ata/libata-scsi.c (ffffffff8179bc95)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff817a1a73)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
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
In drivers/ata/libata-scsi.c (ffffffff8185fa85)
Location: include/linux/libata.h:1818
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-eh.c (ffffffff81865853)
Location: include/linux/libata.h:1818
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libata-sata.c (ffffffff81868635)
Location: include/linux/libata.h:1818
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
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
In drivers/ata/libata-scsi.c (ffffffff8186ea65)
Location: include/linux/libata.h:1818
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-eh.c (ffffffff81874653)
Location: include/linux/libata.h:1818
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libata-sata.c (ffffffff81877445)
Location: include/linux/libata.h:1818
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
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
In drivers/ata/libata-scsi.c (ffffffff81851265)
Location: include/linux/libata.h:1818
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-eh.c (ffffffff81856e43)
Location: include/linux/libata.h:1818
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libata-sata.c (ffffffff81859775)
Location: include/linux/libata.h:1818
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
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
In drivers/ata/libata-scsi.c (ffffffff818dedf5)
Location: include/linux/libata.h:1827
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-eh.c (ffffffff818e56e3)
Location: include/linux/libata.h:1827
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libata-sata.c (ffffffff818e8325)
Location: include/linux/libata.h:1827
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_supported_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
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
In drivers/ata/libata-scsi.c (ffffffff81a30415)
Location: include/linux/libata.h:1823
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-eh.c (ffffffff81a369e3)
Location: include/linux/libata.h:1823
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libata-sata.c (ffffffff81a39de5)
Location: include/linux/libata.h:1823
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_supported_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
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
In drivers/ata/libata-scsi.c (ffffffff81bb3a25)
Location: include/linux/libata.h:1828
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-eh.c (ffffffff81bbb6c3)
Location: include/linux/libata.h:1828
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libata-sata.c (ffffffff81bbf0c5)
Location: include/linux/libata.h:1828
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_supported_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
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
In drivers/ata/libata-scsi.c (ffffffff81c0af45)
Location: include/linux/libata.h:1861
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-eh.c (ffffffff81c12f23)
Location: include/linux/libata.h:1861
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libata-sata.c (ffffffff81c16185)
Location: include/linux/libata.h:1861
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_supported_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
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
In drivers/ata/libata-scsi.c (ffffffff81c5fff5)
Location: include/linux/libata.h:1862
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_slave_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-eh.c (ffffffff81c68043)
Location: include/linux/libata.h:1862
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libata-sata.c (ffffffff81c6b365)
Location: include/linux/libata.h:1862
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/ata/libata-sata.c:ata_scsi_activity_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_show
  - drivers/ata/libata-sata.c:ata_scsi_em_message_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-sata.c:ata_ncq_prio_supported_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_show
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
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
In drivers/ata/libata-scsi.c (ffff8000109a67e8)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffff8000109ad35c)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libahci.c (ffff8000109b97e8)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_show_em_supported
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_show_port_cmd
  - drivers/ata/libahci.c:ahci_show_host_version
  - drivers/ata/libahci.c:ahci_show_host_cap2
  - drivers/ata/libahci.c:ahci_show_host_caps
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
In drivers/ata/libata-scsi.c (c0a76bac)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (c0a7ccd4)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libahci.c (c0a840b8)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_show_em_supported
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_show_port_cmd
  - drivers/ata/libahci.c:ahci_show_host_version
  - drivers/ata/libahci.c:ahci_show_host_cap2
  - drivers/ata/libahci.c:ahci_show_host_caps
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
In drivers/ata/libata-scsi.c (c000000000a6cd38)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (c000000000a74570)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
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
In drivers/ata/libata-scsi.c (ffffffe000605322)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffe00060a764)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
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
In drivers/ata/libata-scsi.c (ffffffff81760d85)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff81766b33)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
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
In drivers/ata/libata-scsi.c (ffffffff81740be5)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff81746993)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
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
In drivers/ata/libata-scsi.c (ffffffff81790b15)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff817968f3)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
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
In drivers/ata/libata-scsi.c (ffffffff817aa955)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
  - drivers/ata/libata-scsi.c:ata_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_type_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_show
  - drivers/ata/libata-scsi.c:ata_scsi_em_message_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffffffff817b0763)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
</details>
</li>
</ul>

## Differences
