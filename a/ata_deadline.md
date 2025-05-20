# Function: <code>ata_deadline</code>

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
In drivers/ata/libata-core.c (ffffffff815c872c)
Location: include/linux/libata.h:1750
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-scsi.c (ffffffff815d1b47)
Location: include/linux/libata.h:1750
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff815d7a2c)
Location: include/linux/libata.h:1750
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff815dddfa)
Location: include/linux/libata.h:1750
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1750
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
In drivers/ata/libata-core.c (ffffffff816219d2)
Location: include/linux/libata.h:1747
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff8162afe7)
Location: include/linux/libata.h:1747
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff816316f6)
Location: include/linux/libata.h:1747
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff81637b9a)
Location: include/linux/libata.h:1747
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff81639bc9)
Location: include/linux/libata.h:1747
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff81652552)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff8165c277)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81662846)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff81668c3a)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff8166ac59)
Location: include/linux/libata.h:1753
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff81666b72)
Location: include/linux/libata.h:1756
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff81671830)
Location: include/linux/libata.h:1756
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8167709f)
Location: include/linux/libata.h:1756
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff8167d46a)
Location: include/linux/libata.h:1756
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff8167f21d)
Location: include/linux/libata.h:1756
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff816d01d2)
Location: include/linux/libata.h:1757
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff816dae10)
Location: include/linux/libata.h:1757
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff816e06d2)
Location: include/linux/libata.h:1757
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff816e6c00)
Location: include/linux/libata.h:1757
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff816e8a7d)
Location: include/linux/libata.h:1757
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff8170cc20)
Location: include/linux/libata.h:1784
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff817172f3)
Location: include/linux/libata.h:1784
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8171cf9f)
Location: include/linux/libata.h:1784
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff817246e2)
Location: include/linux/libata.h:1784
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff817253da)
Location: include/linux/libata.h:1784
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff8172f0a0)
Location: include/linux/libata.h:1783
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff817399a3)
Location: include/linux/libata.h:1783
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8173f87f)
Location: include/linux/libata.h:1783
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff81745c62)
Location: include/linux/libata.h:1783
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff81747b8a)
Location: include/linux/libata.h:1783
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff8176a86e)
Location: include/linux/libata.h:1768
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff8177599a)
Location: include/linux/libata.h:1768
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8177b6af)
Location: include/linux/libata.h:1768
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff81781933)
Location: include/linux/libata.h:1768
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff81783a63)
Location: include/linux/libata.h:1768
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff8178e8de)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff8179990a)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8179f21f)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff817a55d3)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff817a76d3)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff8185275e)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff8185e9d5)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81863c92)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sata.c (ffffffff81868b0e)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff8186ad32)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff8186cbdb)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
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
In drivers/ata/libata-core.c (ffffffff81862abe)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff8186d9f5)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81872a92)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sata.c (ffffffff8187791e)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff81879b42)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff8187b8ab)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
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
In drivers/ata/libata-core.c (ffffffff818458b6)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff8184d3ce)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff818550af)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sata.c (ffffffff8185a0fe)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff8185c292)
Location: include/linux/libata.h:1835
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff8185e90b)
Location: include/linux/libata.h:1835
Inline: True
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
In drivers/ata/libata-core.c (ffffffff818d2346)
Location: include/linux/libata.h:1844
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff818da9fe)
Location: include/linux/libata.h:1844
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff818e3614)
Location: include/linux/libata.h:1844
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sata.c (ffffffff818e8bee)
Location: include/linux/libata.h:1844
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff818eac42)
Location: include/linux/libata.h:1844
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff818ed633)
Location: include/linux/libata.h:1844
Inline: True
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
In drivers/ata/libata-core.c (ffffffff81a22a5f)
Location: include/linux/libata.h:1840
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2eec2)
Location: include/linux/libata.h:1840
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81a3466f)
Location: include/linux/libata.h:1840
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sata.c (ffffffff81a3a461)
Location: include/linux/libata.h:1840
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff81a3bb53)
Location: include/linux/libata.h:1840
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff81a3f966)
Location: include/linux/libata.h:1840
Inline: True
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
In drivers/ata/libata-core.c (ffffffff81ba423f)
Location: include/linux/libata.h:1845
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb23e2)
Location: include/linux/libata.h:1845
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81bb8ed5)
Location: include/linux/libata.h:1845
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sata.c (ffffffff81bbf883)
Location: include/linux/libata.h:1845
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-pmp.c (ffffffff81bc56d8)
Location: include/linux/libata.h:1845
Inline: True
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
In drivers/ata/libata-core.c (ffffffff81bfa93f)
Location: include/linux/libata.h:1878
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff81c09912)
Location: include/linux/libata.h:1878
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81c10776)
Location: include/linux/libata.h:1878
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sata.c (ffffffff81c17373)
Location: include/linux/libata.h:1878
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-pmp.c (ffffffff81c1d185)
Location: include/linux/libata.h:1878
Inline: True
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
In drivers/ata/libata-core.c (ffffffff81c503df)
Location: include/linux/libata.h:1879
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5e9cb)
Location: include/linux/libata.h:1879
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81c659b8)
Location: include/linux/libata.h:1879
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sata.c (ffffffff81c6c429)
Location: include/linux/libata.h:1879
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-pmp.c (ffffffff81c72275)
Location: include/linux/libata.h:1879
Inline: True
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
In drivers/ata/libata-core.c (ffff80001099854c)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffff8000109a41a4)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffff8000109aabf4)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffff8000109b0724)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffff8000109b3fac)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (c0a680b8)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (c0a74304)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (c0a7a518)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (c0a80a78)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (c0a82ed4)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (c000000000a5ad14)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (c000000000a68f8c)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (c000000000a719d4)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (c000000000a7a058)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (c000000000a7ce9c)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffe0005f8e5c)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffe000602620)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffe00060855e)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffe00060e4c0)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffe00061055e)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff81753a4e)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff8175e9fa)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8176430f)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff8176a693)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff8176c793)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff817338ee)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff8173e89a)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8174416f)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff8174a4f3)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff8174c5e3)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff8178375e)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff8178e78a)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8179409f)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff8179a453)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff8179c553)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff8179d61e)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_ready
```
```
In drivers/ata/libata-scsi.c (ffffffff817a866a)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff817adf0f)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sff.c (ffffffff817b42d3)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (ffffffff817b63d3)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
</details>
</li>
</ul>

## Differences
