# Function: <code>early_memunmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff81f8e130)
Location: mm/early_ioremap.c:277
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_read_phys_ulong
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_e820_ext
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_unmap_memmap
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81f8e150-ffffffff81f8e15b: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff81fb871b)
Location: mm/early_ioremap.c:277
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_read_phys_ulong
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
  - arch/x86/platform/efi/efi.c:efi_unmap_memmap
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81fb873b-ffffffff81fb8746: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff81ff508d)
Location: mm/early_ioremap.c:277
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_read_phys_ulong
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
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81ff50ad-ffffffff81ff50b8: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff820d7815)
Location: mm/early_ioremap.c:277
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
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
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff820d7835-ffffffff820d7845: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff826e04f2)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
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
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff826e0512-ffffffff826e0522: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff8270aa0f)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
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
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff8270aa28-ffffffff8270aa38: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828c1bf3)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
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
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff828c1c0c-ffffffff828c1c1c: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828dafe0)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
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
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff828daff9-ffffffff828db009: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828e3416)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
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
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff828e342f-ffffffff828e343f: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff82d00702)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_systab_report_header
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff82d0071b-ffffffff82d0072b: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff82fed0c7)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_systab_report_header
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff82fed0e0-ffffffff82fed0f0: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff831f78f7)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_systab_report_header
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff831f7911-ffffffff831f7921: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff832de662)
Location: mm/early_ioremap.c:295
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_systab_report_header
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff832de67c-ffffffff832de68c: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83493f13)
Location: mm/early_ioremap.c:296
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:get_secrets_page
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_systab_report_header
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
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff83493f3b-ffffffff83493f53: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83ec8304)
Location: mm/early_ioremap.c:296
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:get_secrets_page
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_systab_report_header
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
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff83ec8360-ffffffff83ec8378: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff836ed374)
Location: mm/early_ioremap.c:294
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:get_secrets_page
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_systab_report_header
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
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff836ed3d0-ffffffff836ed3e8: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83920374)
Location: mm/early_ioremap.c:294
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/setup.c:xen_phys_memcpy
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/sev.c:get_secrets_page
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/efi.c:efi_systab_report_header
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
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff839203d0-ffffffff839203e8: early_memunmap (STB_GLOBAL)
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
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffff80001145c910)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/arm64/kernel/acpi.c:__acpi_unmap_table
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
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/arm-init.c:efi_init
  - drivers/firmware/efi/arm-init.c:uefi_init
  - drivers/firmware/efi/arm-init.c:uefi_init
  - drivers/firmware/efi/arm-init.c:uefi_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffff80001145c938-ffff80001145c96c: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (c1534ba8)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
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
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/arm-init.c:efi_init
  - drivers/firmware/efi/arm-init.c:uefi_init
  - drivers/firmware/efi/arm-init.c:uefi_init
  - drivers/firmware/efi/arm-init.c:uefi_init
```
**Symbols:**

```
c1534bc4-c1534be0: early_memunmap (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828cc2ca)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
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
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff828cc2e3-ffffffff828cc2f3: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828c49e6)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
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
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff828c49ff-ffffffff828c4a0f: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828df04a)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
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
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff828df063-ffffffff828df073: early_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void early_memunmap(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828e4461)
Location: mm/early_ioremap.c:300
Inline: True
Inline callers:
  - mm/early_ioremap.c:copy_from_early_mem
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_read_phys_ulong
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/acpi/boot.c:__acpi_unmap_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:update_mp_table
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:get_mpc_size
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/firmware/dmi_scan.c:dmi_setup
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
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap
```
**Symbols:**

```
ffffffff828e447a-ffffffff828e448a: early_memunmap (STB_GLOBAL)
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
