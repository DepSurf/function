# Function: <code>__ata_qc_from_tag</code>

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
In drivers/ata/libata-core.c (ffffffff815cac99)
Location: include/linux/libata.h:1647
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff815d5954)
Location: include/linux/libata.h:1647
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff815dcd3a)
Location: include/linux/libata.h:1647
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
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
Location: include/linux/libata.h:1644
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff8163004c)
Location: include/linux/libata.h:1644
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
```
```
In drivers/ata/libata-sff.c (ffffffff816370a9)
Location: include/linux/libata.h:1644
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
Location: include/linux/libata.h:1650
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff8166119c)
Location: include/linux/libata.h:1650
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
```
```
In drivers/ata/libata-sff.c (ffffffff81668149)
Location: include/linux/libata.h:1650
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
In drivers/ata/libata-core.c (ffffffff81668c66)
Location: include/linux/libata.h:1653
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff81676145)
Location: include/linux/libata.h:1653
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
```
```
In drivers/ata/libata-sff.c (ffffffff8167c88e)
Location: include/linux/libata.h:1653
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
In drivers/ata/libata-core.c (ffffffff816d2316)
Location: include/linux/libata.h:1654
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff816df795)
Location: include/linux/libata.h:1654
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_timed_out
```
```
In drivers/ata/libata-sff.c (ffffffff816e5f6e)
Location: include/linux/libata.h:1654
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
Location: include/linux/libata.h:1681
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff8171bf7f)
Location: include/linux/libata.h:1681
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81722846)
Location: include/linux/libata.h:1681
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
Location: include/linux/libata.h:1680
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff8173e84f)
Location: include/linux/libata.h:1680
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817450f6)
Location: include/linux/libata.h:1680
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
Location: include/linux/libata.h:1665
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff8177a6f6)
Location: include/linux/libata.h:1665
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81780e09)
Location: include/linux/libata.h:1665
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
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff8179e236)
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817a4ab9)
Location: include/linux/libata.h:1667
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
In drivers/ata/libata-core.c (ffffffff81854d3d)
Location: include/linux/libata.h:1732
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff818611d8)
Location: include/linux/libata.h:1732
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81867e95)
Location: include/linux/libata.h:1732
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81869d49)
Location: include/linux/libata.h:1732
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
In drivers/ata/libata-core.c (ffffffff8186500d)
Location: include/linux/libata.h:1732
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff8186fff8)
Location: include/linux/libata.h:1732
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81876ca5)
Location: include/linux/libata.h:1732
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81878b59)
Location: include/linux/libata.h:1732
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
In drivers/ata/libata-core.c (ffffffff81847aad)
Location: include/linux/libata.h:1732
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff81853179)
Location: include/linux/libata.h:1732
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff818594bb)
Location: include/linux/libata.h:1732
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff8185b1c9)
Location: include/linux/libata.h:1732
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
In drivers/ata/libata-core.c (ffffffff818d4a61)
Location: include/linux/libata.h:1741
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff818e4ffe)
Location: include/linux/libata.h:1741
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_finish
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff818e7eea)
Location: include/linux/libata.h:1741
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff818e9cc9)
Location: include/linux/libata.h:1741
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
In drivers/ata/libata-core.c (ffffffff81a25a95)
Location: include/linux/libata.h:1737
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2b34a)
Location: include/linux/libata.h:1737
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81a362fe)
Location: include/linux/libata.h:1737
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_finish
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81a399ca)
Location: include/linux/libata.h:1737
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81a3ca5f)
Location: include/linux/libata.h:1737
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
In drivers/ata/libata-core.c (ffffffff81ba7c61)
Location: include/linux/libata.h:1742
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81bae3da)
Location: include/linux/libata.h:1742
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81bbaf8e)
Location: include/linux/libata.h:1742
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_finish
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81bbeb7c)
Location: include/linux/libata.h:1742
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81bc21bf)
Location: include/linux/libata.h:1742
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
In drivers/ata/libata-core.c (ffffffff81bfe901)
Location: include/linux/libata.h:1775
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81c05b85)
Location: include/linux/libata.h:1775
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81c127ae)
Location: include/linux/libata.h:1775
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_finish
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81c1680c)
Location: include/linux/libata.h:1775
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81c19d6f)
Location: include/linux/libata.h:1775
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
In drivers/ata/libata-core.c (ffffffff81c545f2)
Location: include/linux/libata.h:1776
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81c59bb5)
Location: include/linux/libata.h:1776
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81c67a1e)
Location: include/linux/libata.h:1776
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_finish
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff81c6b94c)
Location: include/linux/libata.h:1776
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/ata/libata-sff.c (ffffffff81c6ee5f)
Location: include/linux/libata.h:1776
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
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffff8000109a9c48)
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sff.c (ffff8000109b135c)
Location: include/linux/libata.h:1667
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
In drivers/ata/libahci.c (ffff8000109bb83c)
Location: include/linux/libata.h:1667
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
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (c0a794a8)
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sff.c (c0a7fcc0)
Location: include/linux/libata.h:1667
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
In drivers/ata/libahci.c (c0a8560c)
Location: include/linux/libata.h:1667
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
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (c000000000a70790)
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sff.c (c000000000a78b8c)
Location: include/linux/libata.h:1667
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
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffe000607790)
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffe00060d668)
Location: include/linux/libata.h:1667
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
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff81763326)
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81769b79)
Location: include/linux/libata.h:1667
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
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff81743186)
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817499d9)
Location: include/linux/libata.h:1667
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
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff817930b6)
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81799939)
Location: include/linux/libata.h:1667
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
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-eh.c (ffffffff817acef6)
Location: include/linux/libata.h:1667
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817b37b9)
Location: include/linux/libata.h:1667
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
</details>
</li>
</ul>

## Differences
