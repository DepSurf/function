# Function: <code>memremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8118b760)
Location: kernel/memremap.c:58
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8118b760-ffffffff8118b86a: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8119e360)
Location: kernel/memremap.c:74
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - kernel/memremap.c:devm_memremap
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
**Symbols:**

```
ffffffff8119e360-ffffffff8119e4d2: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811add90)
Location: kernel/memremap.c:74
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - kernel/memremap.c:devm_memremap
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff811add90-ffffffff811adf02: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811b5250)
Location: kernel/memremap.c:74
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/memremap.c:devm_memremap
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff811b5250-ffffffff811b5389: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811c8a10)
Location: kernel/memremap.c:87
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/memremap.c:devm_memremap
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff811c8a10-ffffffff811c8b90: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff811e8f30)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff811e8f30-ffffffff811e90b8: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff811f9c40)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff811f9c40-ffffffff811f9dc8: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81211b80)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/coherent.c:dma_declare_coherent_memory
  - kernel/iomem.c:devm_memremap
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff81211b80-ffffffff81211d3c: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8121f370)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8121f370-ffffffff8121f52c: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8124b6e0)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/efi.c:efi_debugfs_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8124b6e0-ffffffff8124b7f0: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81255ad0)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/efi.c:efi_debugfs_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff81255ad0-ffffffff81255be0: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8125a050)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/efi.c:efi_debugfs_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8125a050-ffffffff8125a1a0: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/iomem.c (0)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/efi.c:efi_debugfs_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff81cb9c40-ffffffff81cb9c68: memremap.cold (STB_LOCAL)
ffffffff81295e70-ffffffff81295fd8: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/iomem.c (0)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/iomem.c:devm_memremap
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - arch/x86/pci/common.c:pcibios_device_add
```
**Symbols:**

```
ffffffff81e6b23e-ffffffff81e6b266: memremap.cold (STB_LOCAL)
ffffffff812ebc40-ffffffff812ebd83: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/iomem.c (0)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/iomem.c:devm_memremap
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_memreserve_root_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - drivers/clocksource/hyperv_timer.c:hv_remap_tsc_clocksource
  - arch/x86/pci/common.c:pcibios_device_add
```
**Symbols:**

```
ffffffff82061fa7-ffffffff82061fcf: memremap.cold (STB_LOCAL)
ffffffff81355e00-ffffffff81355f43: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/iomem.c (0)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_memreserve_root_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - drivers/clocksource/hyperv_timer.c:hv_remap_tsc_clocksource
  - arch/x86/pci/common.c:pcibios_device_add
```
**Symbols:**

```
ffffffff820e17d5-ffffffff820e17fd: memremap.cold (STB_LOCAL)
ffffffff81387490-ffffffff813875c9: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/iomem.c (0)
Location: kernel/iomem.c:68
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_memreserve_root_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - drivers/clocksource/hyperv_timer.c:hv_remap_tsc_clocksource
  - arch/x86/pci/common.c:pcibios_device_add
```
**Symbols:**

```
ffffffff821be238-ffffffff821be260: memremap.cold (STB_LOCAL)
ffffffff813b0f50-ffffffff813b1089: memremap (STB_GLOBAL)
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
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffff8000102abae8)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/arm64/kernel/crash_dump.c:copy_oldmem_page
  - virt/kvm/kvm_main.c:__kvm_map_gfn
  - kernel/dma/coherent.c:dma_init_coherent_memory
  - kernel/iomem.c:devm_memremap
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/soc/qcom/cmd-db.c:cmd_db_dev_probe
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
```
**Symbols:**

```
ffff8000102abae8-ffff8000102abd8c: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (c04d8e0c)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_init_coherent_memory
  - kernel/iomem.c:devm_memremap
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/soc/qcom/cmd-db.c:cmd_db_dev_probe
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
c04d8e0c-c04d8fdc: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (c00000000035fa60)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_init_coherent_memory
  - kernel/iomem.c:devm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init
```
**Symbols:**

```
c00000000035fa60-c00000000035fcc0: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffe0001d35ec)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_init_coherent_memory
  - kernel/iomem.c:devm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
**Symbols:**

```
ffffffe0001d35ec-ffffffe0001d3750: memremap (STB_GLOBAL)
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
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff812179c0)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff812179c0-ffffffff81217b7c: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8120abd0)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8120abd0-ffffffff8120ad8c: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81215760)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff81215760-ffffffff8121591c: memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *memremap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81224760)
Location: kernel/iomem.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_memreserve_map_root
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff81224760-ffffffff8122491c: memremap (STB_GLOBAL)
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
