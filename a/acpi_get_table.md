# Function: <code>acpi_get_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff814a5c22)
Location: drivers/acpi/acpica/tbxface.c:330
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_acpi.c:read_log
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
```
**Symbols:**

```
ffffffff814a5c22-ffffffff814a5c5d: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff814f4efc)
Location: drivers/acpi/acpica/tbxface.c:330
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_acpi.c:read_log
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
```
**Symbols:**

```
ffffffff814f4efc-ffffffff814f4f37: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81517b92)
Location: drivers/acpi/acpica/tbxface.c:303
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_ecdt_start
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81517b92-ffffffff81517c1c: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815283d4)
Location: drivers/acpi/acpica/tbxface.c:303
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/dmar.c:dmar_table_detect
```
**Symbols:**

```
ffffffff815283d4-ffffffff8152845e: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff8157fdd4)
Location: drivers/acpi/acpica/tbxface.c:331
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/dmar.c:dmar_table_detect
```
**Symbols:**

```
ffffffff8157fdd4-ffffffff8157fe5e: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815b6fcb)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff815b6fcb-ffffffff815b7055: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815d0388)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff815d0388-ffffffff815d0412: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81601c22)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81601c22-ffffffff81601cae: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816230cb)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff816230cb-ffffffff81623157: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816cf7e6)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:dmar_platform_optin
  - drivers/iommu/intel/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff816cf7e6-ffffffff816cf872: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816ed7e6)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/init.c:detect_ivrs
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:dmar_platform_optin
  - drivers/iommu/intel/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff816ed7e6-ffffffff816ed872: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816cf69b)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:dmar_platform_optin
  - drivers/iommu/intel/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff816cf69b-ffffffff816cf727: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81746d0b)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:dmar_platform_optin
  - drivers/iommu/intel/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81746d0b-ffffffff81746d97: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81878cc7)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/acpi/viot.c:acpi_viot_early_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:dmar_platform_optin
  - drivers/iommu/intel/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81878cc7-ffffffff81878d5b: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff819bb1e0)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:check_multiple_madt
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/acpi/viot.c:acpi_viot_early_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff819bb1e0-ffffffff819bb294: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81a02380)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:check_multiple_madt
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/acpi/viot.c:acpi_viot_early_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81a02380-ffffffff81a02434: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81a4d200)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:check_multiple_madt
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/acpi/viot.c:acpi_viot_early_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81a4d200-ffffffff81a4d2b4: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffff8000107985dc)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - arch/arm64/kernel/acpi.c:acpi_boot_table_init
  - drivers/irqchip/irq-gic-v2m.c:acpi_parse_madt_msi
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/pptt.c:find_acpi_cpu_cache_topology
  - drivers/acpi/pptt.c:acpi_pptt_cpu_is_thread
  - drivers/acpi/pptt.c:cache_setup_acpi
  - drivers/acpi/pptt.c:acpi_find_last_cache_level
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/arm64/iort.c:acpi_iort_init
  - drivers/acpi/arm64/gtdt.c:gtdt_sbsa_gwdt_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/firmware/arm_sdei.c:sdei_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffff8000107985dc-ffff800010798698: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815fd075)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff815fd075-ffffffff815fd101: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815e859b)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/nfit/core.c:acpi_nfit_add
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff815e859b-ffffffff815e8627: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816173ab)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff816173ab-ffffffff81617437: acpi_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table(char *signature, u32 instance, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff8163125b)
Location: drivers/acpi/acpica/tbxface.c:297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/processor_core.c:get_madt_table
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff8163125b-ffffffff816312e7: acpi_get_table (STB_GLOBAL)
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
