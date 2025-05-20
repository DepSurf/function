# Function: <code>ata_qc_from_tag</code>

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
In drivers/ata/libata-core.c (ffffffff815cb272)
Location: include/linux/libata.h:1655
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff815d4a27)
Location: include/linux/libata.h:1655
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_nr_in_flight
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff815ddd35)
Location: include/linux/libata.h:1655
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
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
In drivers/ata/libata-core.c (ffffffff81623a8f)
Location: include/linux/libata.h:1652
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff8162e918)
Location: include/linux/libata.h:1652
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_nr_in_flight
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
```
```
In drivers/ata/libata-sff.c (ffffffff81638e18)
Location: include/linux/libata.h:1652
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffff8165460f)
Location: include/linux/libata.h:1658
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff8165fa68)
Location: include/linux/libata.h:1658
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_nr_in_flight
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
```
```
In drivers/ata/libata-sff.c (ffffffff81669eab)
Location: include/linux/libata.h:1658
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81668c3c)
Location: include/linux/libata.h:1661
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff816744b0)
Location: include/linux/libata.h:1661
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
```
```
In drivers/ata/libata-sff.c (ffffffff8167e57d)
Location: include/linux/libata.h:1661
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffff816d22ec)
Location: include/linux/libata.h:1662
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff816ddb10)
Location: include/linux/libata.h:1662
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
```
```
In drivers/ata/libata-sff.c (ffffffff816e7dcd)
Location: include/linux/libata.h:1662
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffff8170ea49)
Location: include/linux/libata.h:1689
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff8171a32c)
Location: include/linux/libata.h:1689
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff8172488d)
Location: include/linux/libata.h:1689
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81730ed9)
Location: include/linux/libata.h:1688
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff8173cc2c)
Location: include/linux/libata.h:1688
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81746e7d)
Location: include/linux/libata.h:1688
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffff8176c683)
Location: include/linux/libata.h:1673
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff8177876c)
Location: include/linux/libata.h:1673
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81782be5)
Location: include/linux/libata.h:1673
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffff817906f3)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff8179c5dc)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817a6895)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-eh.c (ffffffff818611d8)
Location: include/linux/libata.h:1740
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81867872)
Location: include/linux/libata.h:1740
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff8186be7e)
Location: include/linux/libata.h:1740
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-eh.c (ffffffff8186fff8)
Location: include/linux/libata.h:1740
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81876682)
Location: include/linux/libata.h:1740
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff8187ac8e)
Location: include/linux/libata.h:1740
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-eh.c (ffffffff81852808)
Location: include/linux/libata.h:1740
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81858eb2)
Location: include/linux/libata.h:1740
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff8185d4ee)
Location: include/linux/libata.h:1740
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-eh.c (ffffffff818e0649)
Location: include/linux/libata.h:1749
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff818e792a)
Location: include/linux/libata.h:1749
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff818ebda1)
Location: include/linux/libata.h:1749
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-eh.c (ffffffff81a31349)
Location: include/linux/libata.h:1745
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81a390df)
Location: include/linux/libata.h:1745
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81a3e609)
Location: include/linux/libata.h:1745
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-eh.c (ffffffff81bb5739)
Location: include/linux/libata.h:1750
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81bbe162)
Location: include/linux/libata.h:1750
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81bc3d09)
Location: include/linux/libata.h:1750
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-eh.c (ffffffff81c0cc89)
Location: include/linux/libata.h:1783
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81c159ce)
Location: include/linux/libata.h:1783
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81c1b37c)
Location: include/linux/libata.h:1783
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-eh.c (ffffffff81c607d2)
Location: include/linux/libata.h:1784
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
```
In drivers/ata/libata-sata.c (ffffffff81c6aba3)
Location: include/linux/libata.h:1784
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81c7022f)
Location: include/linux/libata.h:1784
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffff80001099a368)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffff8000109a7258)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffff8000109b2c84)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libahci.c (ffff8000109bb83c)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_error_intr
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
In drivers/ata/libata-core.c (c0a6a4bc)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (c0a773dc)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (c0a8205c)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libahci.c (c0a8560c)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_error_intr
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
In drivers/ata/libata-core.c (c000000000a5d7f4)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (c000000000a6d8ec)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (c000000000a7bb18)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffe0005fac98)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffe000605ab0)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffe00060f7be)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81755833)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff817616cc)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff8176b955)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffff817356d3)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff8174152c)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff8174b7b5)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81785573)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff8179145c)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff8179b715)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
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
In drivers/ata/libata-core.c (ffffffff8179f3a3)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-eh.c (ffffffff817ab29c)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817b55b5)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
</details>
</li>
</ul>

## Differences
