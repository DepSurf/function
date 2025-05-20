# Function: <code>ata_is_host_link</code>

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
In drivers/ata/libata-core.c (ffffffff815c74a2)
Location: include/linux/libata.h:1398
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-scsi.c (ffffffff815d18b5)
Location: include/linux/libata.h:1398
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff815d601f)
Location: include/linux/libata.h:1398
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-transport.c (ffffffff815dae1c)
Location: include/linux/libata.h:1398
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff815df5eb)
Location: include/linux/libata.h:1398
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81621036)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff8162de50)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81633118)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff816349fc)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff8163930b)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81651bb6)
Location: include/linux/libata.h:1380
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff8165efa0)
Location: include/linux/libata.h:1380
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81664268)
Location: include/linux/libata.h:1380
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff81665b4c)
Location: include/linux/libata.h:1380
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff8166a39b)
Location: include/linux/libata.h:1380
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81666216)
Location: include/linux/libata.h:1383
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff816739b0)
Location: include/linux/libata.h:1383
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff8167883b)
Location: include/linux/libata.h:1383
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff8167a30e)
Location: include/linux/libata.h:1383
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff8167ea5b)
Location: include/linux/libata.h:1383
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff816cf866)
Location: include/linux/libata.h:1384
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff816dcfa0)
Location: include/linux/libata.h:1384
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff816e1e7b)
Location: include/linux/libata.h:1384
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff816e396e)
Location: include/linux/libata.h:1384
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff816e82bb)
Location: include/linux/libata.h:1384
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff8170c285)
Location: include/linux/libata.h:1388
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff817196e0)
Location: include/linux/libata.h:1388
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff8171e713)
Location: include/linux/libata.h:1388
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff81720202)
Location: include/linux/libata.h:1388
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff81724bdb)
Location: include/linux/libata.h:1388
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff8172e705)
Location: include/linux/libata.h:1387
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff8173bfe0)
Location: include/linux/libata.h:1387
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81740e7d)
Location: include/linux/libata.h:1387
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff81742af2)
Location: include/linux/libata.h:1387
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff8174738b)
Location: include/linux/libata.h:1387
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81769f05)
Location: include/linux/libata.h:1372
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff81777ae1)
Location: include/linux/libata.h:1372
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff8177c8d2)
Location: include/linux/libata.h:1372
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff8177e79f)
Location: include/linux/libata.h:1372
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff8178327b)
Location: include/linux/libata.h:1372
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff8178df65)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff8179ba41)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff817a0997)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff817a245f)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff817a6edb)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81854036)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_force_horkage
  - drivers/ata/libata-core.c:ata_force_xfermask
  - drivers/ata/libata-core.c:ata_force_link_limits
```
```
In drivers/ata/libata-scsi.c (ffffffff8185f831)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff81864fc9)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff81865b5d)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tdev_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-sata.c (ffffffff81868abb)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
  - drivers/ata/libata-sata.c:sata_scr_write_flush
  - drivers/ata/libata-sata.c:sata_scr_write
```
```
In drivers/ata/libata-pmp.c (ffffffff8186cabb)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81864306)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_force_horkage
  - drivers/ata/libata-core.c:ata_force_xfermask
  - drivers/ata/libata-core.c:ata_force_link_limits
```
```
In drivers/ata/libata-scsi.c (ffffffff8186e811)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff81873dc9)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff8187495d)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tdev_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-sata.c (ffffffff818778cb)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
  - drivers/ata/libata-sata.c:sata_scr_write_flush
  - drivers/ata/libata-sata.c:sata_scr_write
```
```
In drivers/ata/libata-pmp.c (ffffffff8187b78b)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff818461f0)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-scsi.c (ffffffff81851011)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff818563fe)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff8185784f)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-sata.c (ffffffff8185a0ab)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
  - drivers/ata/libata-sata.c:sata_scr_write_flush
  - drivers/ata/libata-sata.c:sata_scr_write
```
```
In drivers/ata/libata-pmp.c (ffffffff8185dfdb)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff818d2c1c)
Location: include/linux/libata.h:1446
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-scsi.c (ffffffff818deba1)
Location: include/linux/libata.h:1446
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff818e4b09)
Location: include/linux/libata.h:1446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff818e626f)
Location: include/linux/libata.h:1446
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-sata.c (ffffffff818e8b9b)
Location: include/linux/libata.h:1446
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
  - drivers/ata/libata-sata.c:sata_scr_write_flush
  - drivers/ata/libata-sata.c:sata_scr_write
```
```
In drivers/ata/libata-pmp.c (ffffffff818eccfb)
Location: include/linux/libata.h:1446
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81a2334c)
Location: include/linux/libata.h:1432
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_force_link_limits
```
```
In drivers/ata/libata-scsi.c (ffffffff81a30180)
Location: include/linux/libata.h:1432
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff81a35e95)
Location: include/linux/libata.h:1432
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff81a37722)
Location: include/linux/libata.h:1432
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-sata.c (ffffffff81a3a412)
Location: include/linux/libata.h:1432
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
  - drivers/ata/libata-sata.c:sata_scr_write_flush
  - drivers/ata/libata-sata.c:sata_scr_write
```
```
In drivers/ata/libata-pmp.c (ffffffff81ed9281)
Location: include/linux/libata.h:1432
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81ba512c)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_force_link_limits
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb3740)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff81bba9f0)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff81bbc60e)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-sata.c (ffffffff81bbf81f)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
  - drivers/ata/libata-sata.c:sata_scr_write_flush
  - drivers/ata/libata-sata.c:sata_scr_write
```
```
In drivers/ata/libata-pmp.c (ffffffff81bc49c0)
Location: include/linux/libata.h:1437
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81bfbf89)
Location: include/linux/libata.h:1456
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_force_link_limits
```
```
In drivers/ata/libata-scsi.c (ffffffff81c0ac70)
Location: include/linux/libata.h:1456
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff81c12276)
Location: include/linux/libata.h:1456
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff81c13e7e)
Location: include/linux/libata.h:1456
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-sata.c (ffffffff81c1730f)
Location: include/linux/libata.h:1456
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
  - drivers/ata/libata-sata.c:sata_scr_write_flush
  - drivers/ata/libata-sata.c:sata_scr_write
```
```
In drivers/ata/libata-pmp.c (ffffffff81c1c4d0)
Location: include/linux/libata.h:1456
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81c51bd3)
Location: include/linux/libata.h:1452
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_force_link_limits
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5fd20)
Location: include/linux/libata.h:1452
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff81c67462)
Location: include/linux/libata.h:1452
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff81c6903e)
Location: include/linux/libata.h:1452
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-sata.c (ffffffff81c6c3e2)
Location: include/linux/libata.h:1452
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
  - drivers/ata/libata-sata.c:sata_scr_write_flush
  - drivers/ata/libata-sata.c:sata_scr_write
```
```
In drivers/ata/libata-pmp.c (ffffffff81c715c0)
Location: include/linux/libata.h:1452
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffff800010996f10)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffff8000109a64ec)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffff8000109abed8)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffff8000109ae3c8)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffff8000109b3a6c)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/ata/libahci.c (ffff8000109bb3d4)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_pmp_retry_softreset
  - drivers/ata/libahci.c:ahci_softreset
  - drivers/ata/libahci.c:ahci_do_softreset
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
In drivers/ata/libata-core.c (c0a67558)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (c0a76934)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (c0a7bb80)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (c0a7d884)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (c0a827b8)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/ata/libahci.c (c0a87000)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_pmp_retry_softreset
  - drivers/ata/libahci.c:ahci_softreset
  - drivers/ata/libahci.c:ahci_do_softreset
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
In drivers/ata/libata-core.c (c000000000a59cc8)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (c000000000a6c97c)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (c000000000a730bc)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (c000000000a754cc)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (c000000000a7c5e0)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffe0005f8380)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffe000605042)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffe000609906)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffe00060b336)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffe00060ff94)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff817530f5)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff81760b31)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81765a81)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff8176751f)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff8176bf9b)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81732f95)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff81740991)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff817458e1)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff8174737f)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff8174bdeb)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81782de5)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff817908c1)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81795817)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff817972df)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff8179bd5b)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff8179cca5)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_scr_write_flush
  - drivers/ata/libata-core.c:sata_scr_write
  - drivers/ata/libata-core.c:sata_scr_read
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff817aa701)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff817af687)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-transport.c (ffffffff817b114f)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
```
```
In drivers/ata/libata-pmp.c (ffffffff817b5bdb)
Location: include/linux/libata.h:1374
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
</details>
</li>
</ul>

## Differences
