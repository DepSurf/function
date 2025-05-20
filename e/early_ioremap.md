# Function: <code>early_ioremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - arch/x86/platform/efi/early_printk.c:early_efi_map
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
**Symbols:**

```
ffffffff81f8e0b0-ffffffff81f8e0bb: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (0)
Location: mm/early_ioremap.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_map
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
```
**Symbols:**

```
ffffffff81fb869b-ffffffff81fb86a6: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (0)
Location: mm/early_ioremap.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_map
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
```
**Symbols:**

```
ffffffff81ff500d-ffffffff81ff5018: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff820d776c)
Location: mm/early_ioremap.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_map
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
```
**Symbols:**

```
ffffffff820d776c-ffffffff820d7786: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff826e03ed)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_map
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff826e03ed-ffffffff826e0407: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff8270a8ee)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_map
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff8270a8ee-ffffffff8270a90f: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828c1ad2)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_map
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff828c1ad2-ffffffff828c1af3: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828daeba)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff828daeba-ffffffff828daedb: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828e32f0)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff828e32f0-ffffffff828e3311: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff82d005dc)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff82d005dc-ffffffff82d005fd: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff82fecfa1)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff82fecfa1-ffffffff82fecfc2: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff831f77d5)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff831f77d5-ffffffff831f77f6: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff832de540)
Location: mm/early_ioremap.c:212
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff832de540-ffffffff832de561: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83493dcd)
Location: mm/early_ioremap.c:213
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff83493dcd-ffffffff83493df8: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83ec8130)
Location: mm/early_ioremap.c:213
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff83ec8130-ffffffff83ec815b: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff836ed1a0)
Location: mm/early_ioremap.c:211
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff836ed1a0-ffffffff836ed1cb: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff839201a0)
Location: mm/early_ioremap.c:211
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff839201a0-ffffffff839201cb: early_ioremap (STB_GLOBAL)
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
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffff80001145c714)
Location: mm/early_ioremap.c:217
Inline: False
```
**Symbols:**

```
ffff80001145c714-ffff80001145c774: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (c1534a88)
Location: mm/early_ioremap.c:217
Inline: False
```
**Symbols:**

```
c1534a88-c1534aa8: early_ioremap (STB_GLOBAL)
```
</details>
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
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828cc1a4)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff828cc1a4-ffffffff828cc1c5: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828c48c0)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff828c48c0-ffffffff828c48e1: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828def24)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff828def24-ffffffff828def45: early_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *early_ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828e433b)
Location: mm/early_ioremap.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff828e433b-ffffffff828e435c: early_ioremap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
