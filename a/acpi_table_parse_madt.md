# Function: <code>acpi_table_parse_madt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81fa0a9d)
Location: drivers/acpi/tables.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff81fa0a9d-ffffffff81fa0abc: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81fcc3ae)
Location: drivers/acpi/tables.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff81fcc3ae-ffffffff81fcc3cd: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff820093bc)
Location: drivers/acpi/tables.c:378
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff820093bc-ffffffff820093db: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff820eaa3e)
Location: drivers/acpi/tables.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff820eaa3e-ffffffff820eaa62: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff826f399e)
Location: drivers/acpi/tables.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff826f399e-ffffffff826f39c2: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff8271d974)
Location: drivers/acpi/tables.c:367
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff8271d974-ffffffff8271d998: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828d599f)
Location: drivers/acpi/tables.c:366
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff828d599f-ffffffff828d59c3: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828ef7e5)
Location: drivers/acpi/tables.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff828ef7e5-ffffffff828ef809: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828f8985)
Location: drivers/acpi/tables.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff828f8985-ffffffff828f89a9: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82d0fb70)
Location: drivers/acpi/tables.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_process_madt
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_ioapic_entries
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_ioapic_entries
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_ioapic_entries
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_lapic_entries
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_lapic_entries
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_lapic_entries
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff82d0fb70-ffffffff82d0fb94: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82ffd5b7)
Location: drivers/acpi/tables.c:394
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_process_madt
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_ioapic_entries
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_ioapic_entries
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_ioapic_entries
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_lapic_entries
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_lapic_entries
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_lapic_entries
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff82ffd5b7-ffffffff82ffd5db: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff832082ab)
Location: drivers/acpi/tables.c:394
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff832082ab-ffffffff832082cf: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff832f039c)
Location: drivers/acpi/tables.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff832f039c-ffffffff832f03c0: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff834a82cf)
Location: drivers/acpi/tables.c:449
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff834a82cf-ffffffff834a8302: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83edf8b0)
Location: drivers/acpi/tables.c:459
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff83edf8b0-ffffffff83edf93c: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83705340)
Location: drivers/acpi/tables.c:469
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff83705340-ffffffff837053cc: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83938870)
Location: drivers/acpi/tables.c:297
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff83938870-ffffffff839388fc: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffff80001147ba38)
Location: drivers/acpi/tables.c:405
Inline: False
Direct callers:
  - arch/arm64/kernel/smp.c:smp_init_cpus
  - drivers/irqchip/irq-gic.c:gic_v2_acpi_init
  - drivers/irqchip/irq-gic.c:gic_validate_dist
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_init
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_init
  - drivers/irqchip/irq-gic-v3.c:acpi_validate_gic_table
  - drivers/irqchip/irq-gic-v3.c:acpi_validate_gic_table
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffff80001147ba38-ffff80001147ba88: acpi_table_parse_madt (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828e16f1)
Location: drivers/acpi/tables.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff828e16f1-ffffffff828e1715: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828d9b7c)
Location: drivers/acpi/tables.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff828d9b7c-ffffffff828d9ba0: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828f4581)
Location: drivers/acpi/tables.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff828f4581-ffffffff828f45a5: acpi_table_parse_madt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_table_parse_madt(enum acpi_madt_type id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828f99d9)
Location: drivers/acpi/tables.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/scan.c:__acpi_probe_device_table
```
**Symbols:**

```
ffffffff828f99d9-ffffffff828f99fd: acpi_table_parse_madt (STB_GLOBAL)
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
