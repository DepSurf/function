# Function: <code>memunmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8118b520)
Location: kernel/memremap.c:105
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_release
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8118b520-ffffffff8118b54d: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8119dc20)
Location: kernel/memremap.c:125
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - kernel/memremap.c:devm_memremap_release
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
**Symbols:**

```
ffffffff8119dc20-ffffffff8119dc4f: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811ad640)
Location: kernel/memremap.c:125
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - kernel/memremap.c:devm_memremap_release
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
**Symbols:**

```
ffffffff811ad640-ffffffff811ad66f: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811b4b20)
Location: kernel/memremap.c:125
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/memremap.c:devm_memremap_release
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
**Symbols:**

```
ffffffff811b4b20-ffffffff811b4b50: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811c8b90)
Location: kernel/memremap.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/memremap.c:devm_memremap_release
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff811c8b90-ffffffff811c8bc0: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff811e90c0)
Location: kernel/iomem.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap_release
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff811e90c0-ffffffff811e90ef: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff811f9dd0)
Location: kernel/iomem.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap_release
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff811f9dd0-ffffffff811f9dff: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81211d40)
Location: kernel/iomem.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/coherent.c:dma_release_declared_memory
  - kernel/dma/coherent.c:dma_declare_coherent_memory
  - kernel/dma/coherent.c:dma_declare_coherent_memory
  - kernel/iomem.c:devm_memremap_release
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff81211d40-ffffffff81211d6f: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8121f530)
Location: kernel/iomem.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap_release
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8121f530-ffffffff8121f55f: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8124b8fe)
Location: kernel/iomem.c:122
Inline: True
Inline callers:
  - kernel/iomem.c:devm_memremap_release
Direct callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8124b7f0-ffffffff8124b81b: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81255cee)
Location: kernel/iomem.c:122
Inline: True
Inline callers:
  - kernel/iomem.c:devm_memremap_release
Direct callers:
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff81255be0-ffffffff81255c0b: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8125a2ae)
Location: kernel/iomem.c:122
Inline: True
Inline callers:
  - kernel/iomem.c:devm_memremap_release
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8125a1a0-ffffffff8125a1cb: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8129609e)
Location: kernel/iomem.c:122
Inline: True
Inline callers:
  - kernel/iomem.c:devm_memremap_release
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
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
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff81295e10-ffffffff81295e3b: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff812ebe5d)
Location: kernel/iomem.c:122
Inline: True
Inline callers:
  - kernel/iomem.c:devm_memremap_release
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
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
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_device_add
```
**Symbols:**

```
ffffffff812ebbb0-ffffffff812ebbea: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8135603d)
Location: kernel/iomem.c:122
Inline: True
Inline callers:
  - kernel/iomem.c:devm_memremap_release
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
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
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_device_add
```
**Symbols:**

```
ffffffff81355c70-ffffffff81355caa: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff813876bd)
Location: kernel/iomem.c:122
Inline: True
Inline callers:
  - kernel/iomem.c:devm_memremap_release
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
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
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_device_add
```
**Symbols:**

```
ffffffff81387300-ffffffff8138733a: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff813b0e50)
Location: kernel/iomem.c:119
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
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
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap_release
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_device_add
```
**Symbols:**

```
ffffffff813b0e50-ffffffff813b0eae: memunmap (STB_GLOBAL)
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
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffff8000102ab96c)
Location: kernel/iomem.c:122
Inline: True
Inline callers:
  - kernel/iomem.c:devm_memremap_release
Direct callers:
  - arch/arm64/kernel/crash_dump.c:copy_oldmem_page
  - arch/arm64/kernel/crash_dump.c:copy_oldmem_page
  - virt/kvm/kvm_main.c:__kvm_unmap_gfn
  - kernel/dma/coherent.c:dma_declare_coherent_memory
  - kernel/dma/coherent.c:dma_init_coherent_memory
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
```
**Symbols:**

```
ffff8000102ab8f8-ffff8000102ab948: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (c04d8d4c)
Location: kernel/iomem.c:122
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_declare_coherent_memory
  - kernel/dma/coherent.c:dma_init_coherent_memory
  - kernel/iomem.c:devm_memremap_release
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
c04d8d4c-c04d8d9c: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (c00000000035fcc0)
Location: kernel/iomem.c:122
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_declare_coherent_memory
  - kernel/dma/coherent.c:dma_init_coherent_memory
  - kernel/iomem.c:devm_memremap_release
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_npu2_release
```
**Symbols:**

```
c00000000035fcc0-c00000000035fd28: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffe0001d353c)
Location: kernel/iomem.c:122
Inline: True
Inline callers:
  - kernel/iomem.c:devm_memremap_release
Direct callers:
  - kernel/dma/coherent.c:dma_declare_coherent_memory
  - kernel/dma/coherent.c:dma_init_coherent_memory
  - drivers/nvdimm/core.c:nvdimm_map_put
```
**Symbols:**

```
ffffffe0001d34e0-ffffffe0001d3524: memunmap (STB_GLOBAL)
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
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81217b80)
Location: kernel/iomem.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap_release
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff81217b80-ffffffff81217baf: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8120ad90)
Location: kernel/iomem.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap_release
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8120ad90-ffffffff8120adbf: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81215920)
Location: kernel/iomem.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap_release
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff81215920-ffffffff8121594f: memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memunmap(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81224920)
Location: kernel/iomem.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/iomem.c:devm_memremap_release
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff81224920-ffffffff8122494f: memunmap (STB_GLOBAL)
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
