# Function: <code>ata_dev_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c9540)
Location: drivers/ata/libata-core.c:6851
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff815c9540-ffffffff815c95ca: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81621ce0)
Location: drivers/ata/libata-core.c:7055
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81621ce0-ffffffff81621d6a: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81652860)
Location: drivers/ata/libata-core.c:7097
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81652860-ffffffff816528ea: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81666e80)
Location: drivers/ata/libata-core.c:7183
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81666e80-ffffffff81666f08: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d04e0)
Location: drivers/ata/libata-core.c:7213
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff816d04e0-ffffffff816d0568: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81712f6b)
Location: drivers/ata/libata-core.c:7260
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81712f6b-ffffffff81712ff5: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8173541b)
Location: drivers/ata/libata-core.c:7264
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff8173541b-ffffffff817354a5: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81770e09)
Location: drivers/ata/libata-core.c:7249
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81770e09-ffffffff81770e93: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81794e07)
Location: drivers/ata/libata-core.c:7296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81794e07-ffffffff81794e91: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818590d7)
Location: drivers/ata/libata-core.c:6473
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_zac
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-core.c:ata_force_horkage
  - drivers/ata/libata-core.c:ata_force_xfermask
  - drivers/ata/libata-scsi.c:ata_scsi_remove_dev
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:atapi_eh_clear_ua
  - drivers/ata/libata-eh.c:atapi_eh_clear_ua
  - drivers/ata/libata-eh.c:atapi_eh_clear_ua
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-sata.c:ata_eh_read_log_10h
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff818590d7-ffffffff81859161: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c170ea)
Location: drivers/ata/libata-core.c:6473
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_config_zac
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_non_data
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_dev_config_ncq_send_recv
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-core.c:ata_force_horkage
  - drivers/ata/libata-core.c:ata_force_xfermask
  - drivers/ata/libata-scsi.c:ata_scsi_remove_dev
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:atapi_eh_clear_ua
  - drivers/ata/libata-eh.c:atapi_eh_clear_ua
  - drivers/ata/libata-eh.c:atapi_eh_clear_ua
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-sata.c:ata_eh_read_log_10h
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81c170ea-ffffffff81c17174: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c08db8)
Location: drivers/ata/libata-core.c:6473
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81c08db8-ffffffff81c08e42: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81d0d661)
Location: drivers/ata/libata-core.c:6535
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81d0d661-ffffffff81d0d6eb: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099f840)
Location: drivers/ata/libata-core.c:7296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
```
**Symbols:**

```
ffff80001099f840-ffff80001099f8f4: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6fd38)
Location: drivers/ata/libata-core.c:7296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
```
**Symbols:**

```
c0a6fd38-c0a6fdd4: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a63e44)
Location: drivers/ata/libata-core.c:7296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
```
**Symbols:**

```
c000000000a63e44-c000000000a63ef4: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005ff482)
Location: drivers/ata/libata-core.c:7296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
```
**Symbols:**

```
ffffffe0005ff482-ffffffe0005ff4f2: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81759f17)
Location: drivers/ata/libata-core.c:7296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81759f17-ffffffff81759fa1: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81739db7)
Location: drivers/ata/libata-core.c:7296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81739db7-ffffffff81739e41: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81789c87)
Location: drivers/ata/libata-core.c:7296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81789c87-ffffffff81789d11: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ata_dev_printk(const struct ata_device *dev, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817a3ad7)
Location: drivers/ata/libata-core.c:7296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_dev_same_device
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_tf_read_block
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_maint_in
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_configure
  - drivers/ata/libata-pmp.c:sata_pmp_read_gscr
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff817a3ad7-ffffffff817a3b61: ata_dev_printk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
