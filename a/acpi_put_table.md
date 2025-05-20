# Function: <code>acpi_put_table</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81517a8a)
Location: drivers/acpi/acpica/tbxface.c:365
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff81517a8a-ffffffff81517ad7: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815282cc)
Location: drivers/acpi/acpica/tbxface.c:365
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff815282cc-ffffffff81528319: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff8157ff30)
Location: drivers/acpi/acpica/tbxface.c:393
Inline: True
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff8157ff30-ffffffff8157ffd6: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815b7127)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff815b7127-ffffffff815b71cd: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815d04e4)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff815d04e4-ffffffff815d058a: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81601d80)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff81601d80-ffffffff81601e26: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81623229)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff81623229-ffffffff816232cf: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816cf872)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:dmar_platform_optin
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff816cf872-ffffffff816cf918: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816ed872)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/iommu/amd/init.c:detect_ivrs
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:dmar_platform_optin
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff816ed872-ffffffff816ed918: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816cf727)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:dmar_platform_optin
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff816cf727-ffffffff816cf7cd: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81746d97)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:dmar_platform_optin
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81746d97-ffffffff81746e3d: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81878d5b)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:dmar_platform_optin
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81878d5b-ffffffff81878e0f: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff819bb2b0)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:check_multiple_madt
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/acpi/viot.c:acpi_viot_early_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff819bb2b0-ffffffff819bb383: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81a02450)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:check_multiple_madt
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/acpi/viot.c:acpi_viot_early_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81a02450-ffffffff81a02523: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81a4d2d0)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_amd_sb_acs
  - drivers/acpi/tables.c:check_multiple_madt
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/acpi_lpit.c:acpi_init_lpit
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/acpi/viot.c:acpi_viot_early_init
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81a4d2d0-ffffffff81a4d3a3: acpi_put_table (STB_GLOBAL)
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
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffff800010798698)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - arch/arm64/kernel/acpi.c:acpi_boot_table_init
  - drivers/irqchip/irq-gic-v2m.c:acpi_parse_madt_msi
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/acpi/pptt.c:find_acpi_cpu_cache_topology
  - drivers/acpi/pptt.c:acpi_pptt_cpu_is_thread
  - drivers/acpi/pptt.c:cache_setup_acpi
  - drivers/acpi/pptt.c:acpi_find_last_cache_level
```
**Symbols:**

```
ffff800010798698-ffff800010798708: acpi_put_table (STB_GLOBAL)
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
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815fd101)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff815fd101-ffffffff815fd154: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815e8627)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/nfit/core.c:acpi_nfit_add
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff815e8627-ffffffff815e867a: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81617509)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff81617509-ffffffff816175af: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_put_table(struct acpi_table_header *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816313b9)
Location: drivers/acpi/acpica/tbxface.c:359
Inline: True
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/spcr.c:acpi_parse_spcr
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_platform_optin
  - drivers/iommu/dmar.c:detect_intel_iommu
```
**Symbols:**

```
ffffffff816313b9-ffffffff8163145f: acpi_put_table (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
