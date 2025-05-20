# Function: <code>acpi_get_table_with_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_with_size(char *signature, u32 instance, struct acpi_table_header **out_table, acpi_size *tbl_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff814a5b68)
Location: drivers/acpi/acpica/tbxface.c:282
Inline: True
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/acpica/tbxface.c:acpi_get_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:dmar_table_detect
```
**Symbols:**

```
ffffffff814a5b68-ffffffff814a5c22: acpi_get_table_with_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_with_size(char *signature, u32 instance, struct acpi_table_header **out_table, acpi_size *tbl_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff814f4e43)
Location: drivers/acpi/acpica/tbxface.c:282
Inline: True
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
  - drivers/acpi/acpica/tbxface.c:acpi_get_table
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_table_detect
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff814f4e43-ffffffff814f4efc: acpi_get_table_with_size (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
