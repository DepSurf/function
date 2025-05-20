# Function: <code>ioremap_nocache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106bce0)
Location: arch/x86/mm/ioremap.c:229
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - kernel/memremap.c:ioremap_cache
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:devm_ioremap
  - lib/devres.c:devm_ioremap_nocache
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8106bce0-ffffffff8106bcf9: ioremap_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106bb90)
Location: arch/x86/mm/ioremap.c:228
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - kernel/memremap.c:ioremap_cache
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:devm_ioremap_nocache
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8106bb90-ffffffff8106bba9: ioremap_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f7b0)
Location: arch/x86/mm/ioremap.c:228
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - kernel/memremap.c:ioremap_cache
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:devm_ioremap_nocache
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8106f7b0-ffffffff8106f7c9: ioremap_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106eee0)
Location: arch/x86/mm/ioremap.c:229
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - kernel/memremap.c:ioremap_cache
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8106eee0-ffffffff8106eef9: ioremap_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81073fd0)
Location: arch/x86/mm/ioremap.c:281
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff81073fd0-ffffffff81073fe9: ioremap_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810769e0)
Location: arch/x86/mm/ioremap.c:281
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - arch/x86/platform/efi/early_printk.c:early_efi_map_fb
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:__devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff810769e0-ffffffff810769f9: ioremap_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8107d050)
Location: arch/x86/mm/ioremap.c:282
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - arch/x86/platform/efi/early_printk.c:early_efi_map_fb
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:__devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff8107d050-ffffffff8107d06c: ioremap_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810807a0)
Location: arch/x86/mm/ioremap.c:302
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:__devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff810807a0-ffffffff810807bc: ioremap_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810819a0)
Location: arch/x86/mm/ioremap.c:324
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:__devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff810819a0-ffffffff810819bc: ioremap_nocache (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810809a0)
Location: arch/x86/mm/ioremap.c:324
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:__devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvme/host/pci.c:nvme_remap_bar
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff810809a0-ffffffff810809bc: ioremap_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f8f0)
Location: arch/x86/mm/ioremap.c:324
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:__devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvme/host/pci.c:nvme_remap_bar
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff8106f8f0-ffffffff8106f90c: ioremap_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080950)
Location: arch/x86/mm/ioremap.c:324
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:__devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff81080950-ffffffff8108096c: ioremap_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *ioremap_nocache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81082a70)
Location: arch/x86/mm/ioremap.c:324
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:__devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff81082a70-ffffffff81082a8c: ioremap_nocache (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
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
