# Function: <code>memblock_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181e830)
Location: mm/memblock.c:756
Inline: False
Direct callers:
  - arch/x86/kernel/head.c:reserve_ebda_region
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_set_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff8181e830-ffffffff8181e87f: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81898cd5)
Location: mm/memblock.c:730
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_set_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81898cd5-ffffffff81898d24: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cd37d)
Location: mm/memblock.c:730
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
```
**Symbols:**

```
ffffffff818cd37d-ffffffff818cd3cc: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8190475a)
Location: mm/memblock.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
```
**Symbols:**

```
ffffffff8190475a-ffffffff819047d9: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198e763)
Location: mm/memblock.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
```
**Symbols:**

```
ffffffff8198e763-ffffffff8198e7e2: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819eafe6)
Location: mm/memblock.c:722
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memblock_setup
  - arch/x86/kernel/e820.c:e820__memblock_setup
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_base_nid
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_alloc_range
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff819eafe6-ffffffff819eb065: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a26266)
Location: mm/memblock.c:830
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_base_nid
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_alloc_range
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81a26266-ffffffff81a262e5: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a96a1d)
Location: mm/memblock.c:827
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81a96a1d-ffffffff81a96a9e: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ace28d)
Location: mm/memblock.c:827
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81ace28d-ffffffff81ace30e: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc6f84)
Location: mm/memblock.c:823
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel_low
  - arch/x86/kernel/setup.c:relocate_initrd
  - arch/x86/kernel/e820.c:e820__memblock_setup
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/crash.c:crash_reserve_low_1M
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:allocate_aperture
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81bc6f84-ffffffff81bc7009: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3fca6)
Location: mm/memblock.c:810
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memblock_setup
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/crash.c:crash_reserve_low_1M
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:allocate_aperture
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - drivers/acpi/tables.c:acpi_reserve_initial_tables
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81c3fca6-ffffffff81c3fd2b: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c31d68)
Location: mm/memblock.c:810
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memblock_setup
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/crash.c:crash_reserve_low_1M
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - drivers/acpi/tables.c:acpi_reserve_initial_tables
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81c31d68-ffffffff81c31ded: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d506ff)
Location: mm/memblock.c:837
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/e820.c:e820__memblock_setup
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - drivers/acpi/tables.c:acpi_reserve_initial_tables
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81d506ff-ffffffff81d50784: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f204d8)
Location: mm/memblock.c:838
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/e820.c:e820__memblock_setup
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - drivers/acpi/tables.c:acpi_reserve_initial_tables
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81f204d8-ffffffff81f2056d: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820c9b30)
Location: mm/memblock.c:853
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_setup
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
  - drivers/acpi/tables.c:acpi_reserve_initial_tables
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff820c9b30-ffffffff820c9bca: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214ddb0)
Location: mm/memblock.c:866
Inline: False
Direct callers:
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_setup
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
  - drivers/acpi/tables.c:acpi_reserve_initial_tables
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff8214ddb0-ffffffff8214de4a: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82230970)
Location: mm/memblock.c:906
Inline: False
Direct callers:
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_setup
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
  - drivers/acpi/tables.c:acpi_reserve_initial_tables
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff82230970-ffffffff82230a0a: memblock_reserve (STB_GLOBAL)
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
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031c728)
Location: mm/memblock.c:827
Inline: False
Direct callers:
  - arch/arm64/kernel/setup.c:setup_arch
  - arch/arm64/mm/init.c:arm64_memblock_init
  - arch/arm64/mm/init.c:arm64_memblock_init
  - arch/arm64/mm/init.c:arm64_memblock_init
  - arch/arm64/mm/init.c:arm64_memblock_init
  - arch/arm64/mm/numa.c:numa_init
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/arm-init.c:efi_init
  - drivers/firmware/efi/arm-init.c:reserve_regions
  - drivers/of/fdt.c:early_init_dt_reserve_memory_arch
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
ffff80001031c728-ffff80001031c7dc: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0536628)
Location: mm/memblock.c:827
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/mm/init.c:arm_memblock_init
  - arch/arm/mm/init.c:arm_memblock_init
  - arch/arm/mm/mmu.c:arm_mm_memblock_reserve
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/arm-init.c:efi_init
  - drivers/firmware/efi/arm-init.c:reserve_regions
  - drivers/of/fdt.c:early_init_dt_reserve_memory_arch
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
c0536628-c05366e4: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003f04c0)
Location: mm/memblock.c:827
Inline: False
Direct callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/fadump.c:fadump_reserve_mem
  - arch/powerpc/kernel/fadump.c:fadump_reserve_mem
  - arch/powerpc/kernel/machine_kexec.c:reserve_crashkernel
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_hugepage_blocks
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/of/fdt.c:early_init_dt_reserve_memory_arch
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
c0000000003f04c0-c0000000003f0580: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe0000484d4)
Location: mm/memblock.c:827
Inline: False
Direct callers:
  - arch/riscv/mm/init.c:setup_bootmem
  - arch/riscv/mm/init.c:setup_bootmem
  - arch/riscv/mm/init.c:setup_bootmem
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/of/fdt.c:early_init_dt_reserve_memory_arch
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
ffffffe0000484d4-ffffffe000048536: memblock_reserve (STB_GLOBAL)
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
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6d0fd)
Location: mm/memblock.c:827
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81a6d0fd-ffffffff81a6d17e: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a29644)
Location: mm/memblock.c:827
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81a29644-ffffffff81a296c5: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad950d)
Location: mm/memblock.c:827
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81ad950d-ffffffff81ad958e: memblock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae59c3)
Location: mm/memblock.c:827
Inline: False
Direct callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_add_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_find_free_area
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_double_array
  - mm/memtest.c:reserve_bad_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/memattr.c:efi_memattr_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff81ae59c3-ffffffff81ae5a44: memblock_reserve (STB_GLOBAL)
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
