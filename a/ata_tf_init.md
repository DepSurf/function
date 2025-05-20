# Function: <code>ata_tf_init</code>

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
In drivers/ata/libata-core.c (ffffffff815cacb3)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_do_set_mode
```
```
In drivers/ata/libata-scsi.c (ffffffff815d2fbf)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff815d4fb6)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-pmp.c (ffffffff815df753)
Location: include/linux/libata.h:1675
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff815e1456)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff815e250d)
Location: include/linux/libata.h:1675
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
  - drivers/ata/libata-zpodd.c:zpodd_init
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
In drivers/ata/libata-core.c (ffffffff816234f3)
Location: include/linux/libata.h:1672
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
```
In drivers/ata/libata-scsi.c (ffffffff8162c9bf)
Location: include/linux/libata.h:1672
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff8163304d)
Location: include/linux/libata.h:1672
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff81639473)
Location: include/linux/libata.h:1672
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8163af74)
Location: include/linux/libata.h:1672
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff8163c2f5)
Location: include/linux/libata.h:1672
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffffffff81654073)
Location: include/linux/libata.h:1678
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
```
In drivers/ata/libata-scsi.c (ffffffff8165d80f)
Location: include/linux/libata.h:1678
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff8166419d)
Location: include/linux/libata.h:1678
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff8166a503)
Location: include/linux/libata.h:1678
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8166bff4)
Location: include/linux/libata.h:1678
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff8166d375)
Location: include/linux/libata.h:1678
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816686dd)
Location: include/linux/libata.h:1681
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_set_max_sectors
```
```
In drivers/ata/libata-scsi.c (ffffffff81670b4c)
Location: include/linux/libata.h:1681
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81678ad4)
Location: include/linux/libata.h:1681
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff8167ebb3)
Location: include/linux/libata.h:1681
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff81680565)
Location: include/linux/libata.h:1681
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff816819bc)
Location: include/linux/libata.h:1681
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff81666f40-ffffffff81666f85: ata_tf_init.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d1d5d)
Location: include/linux/libata.h:1682
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_set_max_sectors
```
```
In drivers/ata/libata-scsi.c (ffffffff816da161)
Location: include/linux/libata.h:1682
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff816e2114)
Location: include/linux/libata.h:1682
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff816e8413)
Location: include/linux/libata.h:1682
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff816e9dc5)
Location: include/linux/libata.h:1682
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff816eb1e7)
Location: include/linux/libata.h:1682
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff816d05a0-ffffffff816d05e5: ata_tf_init.isra.15 (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff8170e4f0)
Location: include/linux/libata.h:1709
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
```
In drivers/ata/libata-scsi.c (ffffffff8171663f)
Location: include/linux/libata.h:1709
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff8171e963)
Location: include/linux/libata.h:1709
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff81724d32)
Location: include/linux/libata.h:1709
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff817266d5)
Location: include/linux/libata.h:1709
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff81727b58)
Location: include/linux/libata.h:1709
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffffffff81730970)
Location: include/linux/libata.h:1708
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
```
In drivers/ata/libata-scsi.c (ffffffff81738c7f)
Location: include/linux/libata.h:1708
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff817410cd)
Location: include/linux/libata.h:1708
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff817474e2)
Location: include/linux/libata.h:1708
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff81748e95)
Location: include/linux/libata.h:1708
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff8174a338)
Location: include/linux/libata.h:1708
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffffffff8176c0d0)
Location: include/linux/libata.h:1693
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
```
In drivers/ata/libata-scsi.c (ffffffff81774cc6)
Location: include/linux/libata.h:1693
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff8177cb1a)
Location: include/linux/libata.h:1693
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff817833c2)
Location: include/linux/libata.h:1693
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff81784d25)
Location: include/linux/libata.h:1693
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff817861da)
Location: include/linux/libata.h:1693
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffffffff81790140)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
```
In drivers/ata/libata-scsi.c (ffffffff81798c36)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff817a0be0)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff817a7032)
Location: include/linux/libata.h:1695
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff817a8965)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff817a9e1a)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffffffff81854dd0)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
```
In drivers/ata/libata-scsi.c (ffffffff8185a3bf)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_request_sense
```
```
In drivers/ata/libata-eh.c (ffffffff81861cb2)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff8186cc9b)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
```
In drivers/ata/libata-acpi.c (ffffffff8186e1c5)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff8186f6d4)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
  - drivers/ata/libata-zpodd.c:zpodd_get_mech_type
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
In drivers/ata/libata-core.c (ffffffff818650a0)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
```
In drivers/ata/libata-scsi.c (ffffffff818694bf)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_request_sense
```
```
In drivers/ata/libata-eh.c (ffffffff81870ac2)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff8187b96b)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
```
In drivers/ata/libata-acpi.c (ffffffff8187ce95)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff8187e3a4)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
  - drivers/ata/libata-zpodd.c:zpodd_get_mech_type
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
In drivers/ata/libata-core.c (ffffffff81847b40)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
```
In drivers/ata/libata-scsi.c (ffffffff8184beef)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_request_sense
```
```
In drivers/ata/libata-eh.c (ffffffff818531e4)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff8185e0c3)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
```
In drivers/ata/libata-acpi.c (ffffffff8185f705)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff81860bda)
Location: include/linux/libata.h:1760
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffffffff818d4afe)
Location: include/linux/libata.h:1769
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
```
In drivers/ata/libata-scsi.c (ffffffff818d934f)
Location: include/linux/libata.h:1769
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_request_sense
```
```
In drivers/ata/libata-eh.c (ffffffff818e1233)
Location: include/linux/libata.h:1769
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff818ecde3)
Location: include/linux/libata.h:1769
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
```
In drivers/ata/libata-acpi.c (ffffffff818ee4c5)
Location: include/linux/libata.h:1769
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff818ef9da)
Location: include/linux/libata.h:1769
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffffffff81a2625f)
Location: include/linux/libata.h:1765
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2aa32)
Location: include/linux/libata.h:1765
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_request_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81ed8492)
Location: include/linux/libata.h:1765
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff81a3f273)
Location: include/linux/libata.h:1765
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
```
In drivers/ata/libata-acpi.c (ffffffff81a40695)
Location: include/linux/libata.h:1765
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff81a41bea)
Location: include/linux/libata.h:1765
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffffffff81ba846f)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
```
```
In drivers/ata/libata-scsi.c (ffffffff81bad652)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_request_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81bb54c5)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff81bc4d03)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
```
In drivers/ata/libata-acpi.c (ffffffff81bc6858)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff81bc7f8a)
Location: include/linux/libata.h:1770
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffffffff81bff10f)
Location: include/linux/libata.h:1803
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
```
```
In drivers/ata/libata-scsi.c (ffffffff81c04b92)
Location: include/linux/libata.h:1803
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_request_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81c0c995)
Location: include/linux/libata.h:1803
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff81c1c813)
Location: include/linux/libata.h:1803
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
```
In drivers/ata/libata-acpi.c (ffffffff81c1e1d5)
Location: include/linux/libata.h:1803
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff81c1fb1a)
Location: include/linux/libata.h:1803
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffffffff81c5515f)
Location: include/linux/libata.h:1804
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_power_set_active
  - drivers/ata/libata-core.c:ata_dev_power_is_active
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
```
```
In drivers/ata/libata-scsi.c (ffffffff81c59c55)
Location: include/linux/libata.h:1804
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
```
In drivers/ata/libata-eh.c (ffffffff81c61b65)
Location: include/linux/libata.h:1804
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff81c71903)
Location: include/linux/libata.h:1804
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
```
In drivers/ata/libata-acpi.c (ffffffff81c732d5)
Location: include/linux/libata.h:1804
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff81c74ca9)
Location: include/linux/libata.h:1804
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffff800010999d84)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
```
In drivers/ata/libata-scsi.c (ffff8000109a0ef8)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffff8000109ac01c)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffff8000109b35d0)
Location: include/linux/libata.h:1695
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffff8000109b529c)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffff8000109b6b24)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
```
In drivers/ata/libahci.c (ffff8000109b938c)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_do_hardreset
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
In drivers/ata/libata-core.c (c0a69d64)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (c0a70da8)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (c0a7bf80)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (c0a8295c)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
```
In drivers/ata/libahci.c (c0a87558)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_do_hardreset
  - drivers/ata/libahci.c:ahci_do_softreset
```
```
In drivers/ata/sata_highbank.c (c0a89508)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/sata_highbank.c:ahci_highbank_hardreset
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
In drivers/ata/libata-core.c (c000000000a5cfac)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
```
In drivers/ata/libata-scsi.c (c000000000a651b0)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (c000000000a732e0)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (c000000000a7c7bc)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
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
In drivers/ata/libata-core.c (ffffffe0005fa79c)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
```
In drivers/ata/libata-scsi.c (ffffffe000600734)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffe000609854)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffe0006100d6)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
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
In drivers/ata/libata-core.c (ffffffff817552b0)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
```
In drivers/ata/libata-scsi.c (ffffffff8175dd26)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81765cb2)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff8176c0f2)
Location: include/linux/libata.h:1695
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8176da25)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
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
In drivers/ata/libata-core.c (ffffffff81735150)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
```
In drivers/ata/libata-scsi.c (ffffffff8173dbc6)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81745b12)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff8174bf42)
Location: include/linux/libata.h:1695
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8174d875)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
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
In drivers/ata/libata-core.c (ffffffff81784fc0)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
```
In drivers/ata/libata-scsi.c (ffffffff8178dab6)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81795a60)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff8179beb2)
Location: include/linux/libata.h:1695
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8179d7e5)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff8179ec9a)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
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
In drivers/ata/libata-core.c (ffffffff8179edb0)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_new_init
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
```
In drivers/ata/libata-scsi.c (ffffffff817a7906)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff817af8d0)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
```
```
In drivers/ata/libata-pmp.c (ffffffff817b5d32)
Location: include/linux/libata.h:1695
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff817b7665)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_gtf_to_tf
```
```
In drivers/ata/libata-zpodd.c (ffffffff817b8b1a)
Location: include/linux/libata.h:1695
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
</details>
</li>
</ul>

## Differences
