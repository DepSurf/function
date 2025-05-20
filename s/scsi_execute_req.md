# Function: <code>scsi_execute_req</code>

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
In drivers/scsi/scsi.c (ffffffff815a6464)
Location: include/scsi/scsi_device.h:407
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff815a8b6f)
Location: include/scsi/scsi_device.h:407
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff815af011)
Location: include/scsi/scsi_device.h:407
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b20b6)
Location: include/scsi/scsi_device.h:407
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/sd.c (ffffffff815bccba)
Location: include/scsi/scsi_device.h:407
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_pr_command
```
```
In drivers/scsi/sr.c (ffffffff815c033e)
Location: include/scsi/scsi_device.h:407
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/scsi.c (ffffffff815fe8b6)
Location: include/scsi/scsi_device.h:418
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81600a1f)
Location: include/scsi/scsi_device.h:418
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8160783c)
Location: include/scsi/scsi_device.h:418
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160b2fd)
Location: include/scsi/scsi_device.h:418
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff8161692e)
Location: include/scsi/scsi_device.h:418
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_pr_command
```
```
In drivers/scsi/sr.c (ffffffff81618e10)
Location: include/scsi/scsi_device.h:418
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff8162def6)
Location: include/scsi/scsi_device.h:419
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816300ff)
Location: include/scsi/scsi_device.h:419
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81636f0c)
Location: include/scsi/scsi_device.h:419
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff8163abb7)
Location: include/scsi/scsi_device.h:419
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff816463cf)
Location: include/scsi/scsi_device.h:419
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_pr_command
```
```
In drivers/scsi/sd_zbc.c (ffffffff81648066)
Location: include/scsi/scsi_device.h:419
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff81649a90)
Location: include/scsi/scsi_device.h:419
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff81643316)
Location: include/scsi/scsi_device.h:418
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81644e9f)
Location: include/scsi/scsi_device.h:418
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164976c)
Location: include/scsi/scsi_device.h:418
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff8164fb11)
Location: include/scsi/scsi_device.h:418
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff8165af55)
Location: include/scsi/scsi_device.h:418
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165cb06)
Location: include/scsi/scsi_device.h:418
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8165e420)
Location: include/scsi/scsi_device.h:418
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff816ac426)
Location: include/scsi/scsi_device.h:434
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816ade2f)
Location: include/scsi/scsi_device.h:434
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b298c)
Location: include/scsi/scsi_device.h:434
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b9109)
Location: include/scsi/scsi_device.h:434
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff816c45a5)
Location: include/scsi/scsi_device.h:434
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6166)
Location: include/scsi/scsi_device.h:434
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff816c79a0)
Location: include/scsi/scsi_device.h:434
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff816e8956)
Location: include/scsi/scsi_device.h:434
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816ea22b)
Location: include/scsi/scsi_device.h:434
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816eeafc)
Location: include/scsi/scsi_device.h:434
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f5438)
Location: include/scsi/scsi_device.h:434
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff81700af9)
Location: include/scsi/scsi_device.h:434
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff817026e6)
Location: include/scsi/scsi_device.h:434
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff817043a3)
Location: include/scsi/scsi_device.h:434
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff8170c456)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8170dcdb)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8171269c)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff81717d87)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff81723899)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff8172530b)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81727163)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff81747b76)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8174949b)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174e00c)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff81753097)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff8175cbcf)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81760960)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81762899)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff8176bcc6)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8176d5cb)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff817721bc)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff81777317)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff81780a9f)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81784900)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81786889)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff8182df36)
Location: include/scsi/scsi_device.h:455
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8182fc49)
Location: include/scsi/scsi_device.h:455
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818346ec)
Location: include/scsi/scsi_device.h:455
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff8183a227)
Location: include/scsi/scsi_device.h:455
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff8184703c)
Location: include/scsi/scsi_device.h:455
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff818485e5)
Location: include/scsi/scsi_device.h:455
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff8184a09e)
Location: include/scsi/scsi_device.h:455
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_get_events
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
In drivers/scsi/scsi.c (ffffffff8183ef76)
Location: include/scsi/scsi_device.h:456
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81840909)
Location: include/scsi/scsi_device.h:456
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818450cc)
Location: include/scsi/scsi_device.h:456
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184abe7)
Location: include/scsi/scsi_device.h:456
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff81856a4a)
Location: include/scsi/scsi_device.h:456
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81858ad5)
Location: include/scsi/scsi_device.h:456
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff8185a74e)
Location: include/scsi/scsi_device.h:456
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_get_events
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
In drivers/scsi/scsi.c (ffffffff81822186)
Location: include/scsi/scsi_device.h:457
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81823b4b)
Location: include/scsi/scsi_device.h:457
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182825c)
Location: include/scsi/scsi_device.h:457
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182df48)
Location: include/scsi/scsi_device.h:457
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff818397da)
Location: include/scsi/scsi_device.h:457
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183ba57)
Location: include/scsi/scsi_device.h:457
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff8183da4e)
Location: include/scsi/scsi_device.h:457
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff818acac6)
Location: include/scsi/scsi_device.h:464
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff818ae47b)
Location: include/scsi/scsi_device.h:464
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b3b9c)
Location: include/scsi/scsi_device.h:464
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b9d18)
Location: include/scsi/scsi_device.h:464
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff818c5e5a)
Location: include/scsi/scsi_device.h:464
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8127)
Location: include/scsi/scsi_device.h:464
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff818ca50e)
Location: include/scsi/scsi_device.h:464
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff819f7877)
Location: include/scsi/scsi_device.h:472
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_get_vpd_size
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff819f95c5)
Location: include/scsi/scsi_device.h:472
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a009cc)
Location: include/scsi/scsi_device.h:472
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a056b8)
Location: include/scsi/scsi_device.h:472
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff81a128d2)
Location: include/scsi/scsi_device.h:472
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a14f8e)
Location: include/scsi/scsi_device.h:472
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81a179dd)
Location: include/scsi/scsi_device.h:472
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff81b750d7)
Location: include/scsi/scsi_device.h:473
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_get_vpd_size
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81b77585)
Location: include/scsi/scsi_device.h:473
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7f06c)
Location: include/scsi/scsi_device.h:473
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b843c5)
Location: include/scsi/scsi_device.h:473
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff81b92c52)
Location: include/scsi/scsi_device.h:473
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b95bde)
Location: include/scsi/scsi_device.h:473
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81b988ed)
Location: include/scsi/scsi_device.h:473
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_check_events
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/scsi/scsi.c (ffff80001096dcac)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffff80001096fda8)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffff8000109759b4)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffff80001097b680)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffff800010987200)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffff80001098b100)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/sr.c (ffff80001098d370)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (c0a43714)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (c0a44f3c)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/scsi_lib.c (c0a49f30)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (c0a4f480)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (c0a599bc)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (c0a5d418)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (c0a5f554)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (c000000000a270bc)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (c000000000a29498)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/scsi_lib.c (c000000000a2f82c)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (c000000000a36928)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (c000000000a471c4)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (c000000000a4bc68)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (c000000000a4e894)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffe0005d8560)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffe0005d9c8c)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005ddee8)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e263c)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffe0005ebade)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005ef512)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffe0005f11c6)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff817203b6)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81721cbb)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff817268ac)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172ba07)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff8173518f)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81738ff0)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff8173af79)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff816f97e6)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816fb0eb)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ffcdc)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff81704e27)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff81716e2f)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171ac90)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff8171cc19)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff8175f186)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81760a8b)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8176567c)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff8176a7d7)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772736)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
```
```
In drivers/scsi/sd.c (ffffffff8177591f)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81779780)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff8177b709)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
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
In drivers/scsi/scsi.c (ffffffff8177a7e6)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
  - drivers/scsi/scsi.c:scsi_vpd_inquiry
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8177c0eb)
Location: include/scsi/scsi_device.h:446
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81780d0c)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_test_unit_ready
  - drivers/scsi/scsi_lib.c:scsi_mode_sense
  - drivers/scsi/scsi_lib.c:scsi_mode_select
```
```
In drivers/scsi/scsi_scan.c (ffffffff81785f27)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
```
In drivers/scsi/sd.c (ffffffff8178f6ff)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff817935b0)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81795539)
Location: include/scsi/scsi_device.h:446
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
```
</details>
</li>
</ul>

## Differences
