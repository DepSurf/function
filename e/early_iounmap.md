# Function: <code>early_iounmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff81f8df74)
Location: mm/early_ioremap.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - arch/x86/platform/efi/early_printk.c:early_efi_unmap
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
**Symbols:**

```
ffffffff81f8df74-ffffffff81f8e09b: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff81fb8566)
Location: mm/early_ioremap.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_unmap
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
```
**Symbols:**

```
ffffffff81fb8566-ffffffff81fb8686: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff81ff4ed8)
Location: mm/early_ioremap.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_unmap
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
```
**Symbols:**

```
ffffffff81ff4ed8-ffffffff81ff4ff8: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff820d7677)
Location: mm/early_ioremap.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_unmap
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
```
**Symbols:**

```
ffffffff820d7677-ffffffff820d776c: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff826e02f2)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_unmap
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff826e02f2-ffffffff826e03ed: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff8270a7e8)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_unmap
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff8270a7e8-ffffffff8270a8ee: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828c19cc)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/platform/efi/early_printk.c:early_efi_unmap
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff828c19cc-ffffffff828c1ad2: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828dada9)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff828dada9-ffffffff828daeba: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828e31eb)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff828e31eb-ffffffff828e32f0: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff82d004d7)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff82d004d7-ffffffff82d005dc: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff82fece9c)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff82fece9c-ffffffff82fecfa1: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff831f76ba)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff831f76ba-ffffffff831f77d5: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff832de3cb)
Location: mm/early_ioremap.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff832de3cb-ffffffff832de540: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83493c42)
Location: mm/early_ioremap.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff83493c42-ffffffff83493dcd: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83ec7f30)
Location: mm/early_ioremap.c:164
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff83ec7f30-ffffffff83ec811c: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff836ecf90)
Location: mm/early_ioremap.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff836ecf90-ffffffff836ed188: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff8391ff90)
Location: mm/early_ioremap.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8391ff90-ffffffff83920188: early_iounmap (STB_GLOBAL)
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
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffff80001145c5d0)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - mm/early_ioremap.c:copy_from_early_mem
```
**Symbols:**

```
ffff80001145c5d0-ffff80001145c714: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (c1534910)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - mm/early_ioremap.c:copy_from_early_mem
```
**Symbols:**

```
c1534910-c1534a88: early_iounmap (STB_GLOBAL)
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
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828cc09f)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff828cc09f-ffffffff828cc1a4: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828c47bf)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff828c47bf-ffffffff828c48c0: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828dee1f)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff828dee1f-ffffffff828def24: early_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void early_iounmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828e4236)
Location: mm/early_ioremap.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff828e4236-ffffffff828e433b: early_iounmap (STB_GLOBAL)
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
