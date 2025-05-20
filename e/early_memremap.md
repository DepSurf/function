# Function: <code>early_memremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff81f8e09b)
Location: mm/early_ioremap.c:216
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_e820_ext
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81f8e09b-ffffffff81f8e0b0: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff81fb8686)
Location: mm/early_ioremap.c:216
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_e820_ext
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81fb8686-ffffffff81fb869b: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff81ff4ff8)
Location: mm/early_ioremap.c:216
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_e820_ext
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81ff4ff8-ffffffff81ff500d: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (0)
Location: mm/early_ioremap.c:216
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff820d7786-ffffffff820d7796: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff826e0407)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff826e0407-ffffffff826e0442: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff8270a90f)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff8270a90f-ffffffff8270a951: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828c1af3)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff828c1af3-ffffffff828c1b35: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828daedb)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff828daedb-ffffffff828daf1f: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828e3311)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff828e3311-ffffffff828e3355: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff82d005fd)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff82d005fd-ffffffff82d00641: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff82fecfc2)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff82fecfc2-ffffffff82fed006: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff831f77f6)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff831f77f6-ffffffff831f783a: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff832de561)
Location: mm/early_ioremap.c:219
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff832de561-ffffffff832de5a5: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83493df8)
Location: mm/early_ioremap.c:220
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:get_secrets_page
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff83493df8-ffffffff83493e44: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83ec82d2)
Location: mm/early_ioremap.c:220
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:get_secrets_page
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff83ec8170-ffffffff83ec81bc: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff836ed342)
Location: mm/early_ioremap.c:218
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:get_secrets_page
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff836ed1e0-ffffffff836ed22c: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83920342)
Location: mm/early_ioremap.c:218
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:get_secrets_page
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff839201e0-ffffffff8392022c: early_memremap (STB_GLOBAL)
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
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffff80001145c774)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/arm64/kernel/acpi.c:__acpi_map_table
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffff80001145c774-ffff80001145c7e4: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (c1534aa8)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
c1534aa8-c1534aec: early_memremap (STB_GLOBAL)
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
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828cc1c5)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff828cc1c5-ffffffff828cc209: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828c48e1)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff828c48e1-ffffffff828c4925: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828def45)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff828def45-ffffffff828def89: early_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *early_memremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828e435c)
Location: mm/early_ioremap.c:224
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_map_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - mm/early_ioremap.c:copy_from_early_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff828e435c-ffffffff828e43a0: early_memremap (STB_GLOBAL)
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
