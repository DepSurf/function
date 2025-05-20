# Function: <code>ata_tag_valid</code>

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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1501
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1501
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/libata.h:1501
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1501
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1477
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1477
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/libata.h:1477
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1477
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1483
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1483
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/libata.h:1483
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1483
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1486
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1486
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/libata.h:1486
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1486
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1487
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1487
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/libata.h:1487
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1487
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
In drivers/ata/libata-core.c (ffffffff8170eade)
Location: include/linux/libata.h:1496
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff8171e90e)
Location: include/linux/libata.h:1496
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81722846)
Location: include/linux/libata.h:1496
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff81724cd0)
Location: include/linux/libata.h:1496
Inline: True
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
In drivers/ata/libata-core.c (ffffffff81730f6e)
Location: include/linux/libata.h:1495
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff81741078)
Location: include/linux/libata.h:1495
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817450f6)
Location: include/linux/libata.h:1495
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff81747480)
Location: include/linux/libata.h:1495
Inline: True
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
In drivers/ata/libata-core.c (ffffffff8176c71d)
Location: include/linux/libata.h:1480
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff8177cac5)
Location: include/linux/libata.h:1480
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81780e09)
Location: include/linux/libata.h:1480
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff81783360)
Location: include/linux/libata.h:1480
Inline: True
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
In drivers/ata/libata-core.c (ffffffff8179078d)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff817a0b8b)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817a4ab9)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff817a6fd0)
Location: include/linux/libata.h:1482
Inline: True
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
In drivers/ata/libata-core.c (ffffffff8185533d)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff81861c3c)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81867f16)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81869d49)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff8186c634)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_qc_defer_cmd_switch
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
In drivers/ata/libata-core.c (ffffffff8186557d)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff81870a4c)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81876d26)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81878b59)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff8187b324)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_qc_defer_cmd_switch
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
In drivers/ata/libata-core.c (ffffffff8184801d)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff8185316f)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81858eb2)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff8185b1c9)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff8185db80)
Location: include/linux/libata.h:1545
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_qc_defer_cmd_switch
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
In drivers/ata/libata-core.c (ffffffff818d5046)
Location: include/linux/libata.h:1554
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff818e11b1)
Location: include/linux/libata.h:1554
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff818e792a)
Location: include/linux/libata.h:1554
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff818e9cc9)
Location: include/linux/libata.h:1554
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff818ec890)
Location: include/linux/libata.h:1554
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_qc_defer_cmd_switch
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
In drivers/ata/libata-core.c (ffffffff81a25777)
Location: include/linux/libata.h:1550
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2b34a)
Location: include/linux/libata.h:1550
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81a31182)
Location: include/linux/libata.h:1550
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81a390df)
Location: include/linux/libata.h:1550
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81a3ca5f)
Location: include/linux/libata.h:1550
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff81a3f0bc)
Location: include/linux/libata.h:1550
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
In drivers/ata/libata-core.c (ffffffff81ba7937)
Location: include/linux/libata.h:1555
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81bae3da)
Location: include/linux/libata.h:1555
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81bb5431)
Location: include/linux/libata.h:1555
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81bbe162)
Location: include/linux/libata.h:1555
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81bc21bf)
Location: include/linux/libata.h:1555
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff81bc4adc)
Location: include/linux/libata.h:1555
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
In drivers/ata/libata-core.c (ffffffff81bfe5c7)
Location: include/linux/libata.h:1574
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81c05b85)
Location: include/linux/libata.h:1574
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81c0c901)
Location: include/linux/libata.h:1574
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81c159ce)
Location: include/linux/libata.h:1574
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81c19d6f)
Location: include/linux/libata.h:1574
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff81c1c5ec)
Location: include/linux/libata.h:1574
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
In drivers/ata/libata-core.c (ffffffff81c542b8)
Location: include/linux/libata.h:1575
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81c59bb5)
Location: include/linux/libata.h:1575
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81c61ad1)
Location: include/linux/libata.h:1575
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
```
```
In drivers/ata/libata-sata.c (ffffffff81c6aba3)
Location: include/linux/libata.h:1575
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81c6ee5f)
Location: include/linux/libata.h:1575
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff81c716dc)
Location: include/linux/libata.h:1575
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
In drivers/ata/libata-core.c (ffff80001099a42c)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffff8000109abfdc)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffff8000109b135c)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffff8000109b3548)
Location: include/linux/libata.h:1482
Inline: True
```
```
In drivers/ata/libahci.c (ffff8000109bb83c)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_error_intr
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
In drivers/ata/libata-core.c (c0a6a5e4)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (c0a7bf40)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (c0a7fcc0)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (c0a828c8)
Location: include/linux/libata.h:1482
Inline: True
```
```
In drivers/ata/libahci.c (c0a8560c)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_error_intr
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
In drivers/ata/libata-core.c (c000000000a5d8f8)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (c000000000a7329c)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (c000000000a78b8c)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (c000000000a7c714)
Location: include/linux/libata.h:1482
Inline: True
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
In drivers/ata/libata-core.c (ffffffe0005fadb0)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffe0006097cc)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffe00060d668)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffe000610072)
Location: include/linux/libata.h:1482
Inline: True
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
In drivers/ata/libata-core.c (ffffffff817558cd)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff81765c5d)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81769b79)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff8176c090)
Location: include/linux/libata.h:1482
Inline: True
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
In drivers/ata/libata-core.c (ffffffff8173576d)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff81745abd)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817499d9)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff8174bee0)
Location: include/linux/libata.h:1482
Inline: True
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
In drivers/ata/libata-core.c (ffffffff8178560d)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff81795a0b)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81799939)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff8179be50)
Location: include/linux/libata.h:1482
Inline: True
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
In drivers/ata/libata-core.c (ffffffff8179f43d)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_free
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_std_qc_defer
  - drivers/ata/libata-core.c:ata_std_qc_defer
```
```
In drivers/ata/libata-eh.c (ffffffff817af87b)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817b37b9)
Location: include/linux/libata.h:1482
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_hsm_qc_complete
```
```
In drivers/ata/libata-pmp.c (ffffffff817b5cd0)
Location: include/linux/libata.h:1482
Inline: True
```
</details>
</li>
</ul>

## Differences
