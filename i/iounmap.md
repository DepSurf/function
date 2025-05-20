# Function: <code>iounmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106bdd0)
Location: arch/x86/mm/ioremap.c:335
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
Direct callers:
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - kernel/memremap.c:devm_memremap_release
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_ioremap_release
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_ports
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8106bdd0-ffffffff8106be51: iounmap.part.1 (STB_LOCAL)
ffffffff8106be60-ffffffff8106be8f: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106bc80)
Location: arch/x86/mm/ioremap.c:334
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - kernel/memremap.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8106bc80-ffffffff8106bd32: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f8a0)
Location: arch/x86/mm/ioremap.c:334
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - kernel/memremap.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8106f8a0-ffffffff8106f952: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106efc0)
Location: arch/x86/mm/ioremap.c:335
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr
  - kernel/memremap.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/sfi/sfi_core.c:sfi_unmap_memory
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
  - arch/x86/pci/common.c:pcibios_add_device
```
**Symbols:**

```
ffffffff8106efc0-ffffffff8106f073: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810740b0)
Location: arch/x86/mm/ioremap.c:387
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/memremap.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff810740b0-ffffffff81074176: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:387
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/iomem.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff81076e44-ffffffff81076e5d: iounmap.cold.16 (STB_LOCAL)
ffffffff81076ac0-ffffffff81076b70: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8107d18a)
Location: arch/x86/mm/ioremap.c:395
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/iomem.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff8107d4d4-ffffffff8107d4ed: iounmap.cold.16 (STB_LOCAL)
ffffffff8107d150-ffffffff8107d200: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080a2b)
Location: arch/x86/mm/ioremap.c:415
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/iomem.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff81080da6-ffffffff81080dbf: iounmap.cold (STB_LOCAL)
ffffffff810809f0-ffffffff81080aa1: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81081aeb)
Location: arch/x86/mm/ioremap.c:437
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - kernel/iomem.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_cleanup
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff81081e66-ffffffff81081e7f: iounmap.cold (STB_LOCAL)
ffffffff81081ab0-ffffffff81081b61: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088ad0)
Location: arch/x86/mm/ioremap.c:437
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - kernel/iomem.c:devm_memremap_release
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_acpi_add
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/cpufreq/pcc-cpufreq.c:pcc_clear_mapping
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff81088a50-ffffffff81088ac3: iounmap.part.0 (STB_LOCAL)
ffffffff81088f11-ffffffff81088f2a: iounmap.part.0.cold (STB_LOCAL)
ffffffff81088ad0-ffffffff81088b18: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088d10)
Location: arch/x86/mm/ioremap.c:437
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/sev-es.c:sev_es_setup_ap_jump_table
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - kernel/iomem.c:devm_memremap_release
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_acpi_add
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/cpufreq/pcc-cpufreq.c:pcc_clear_mapping
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff81088c90-ffffffff81088d03: iounmap.part.0 (STB_LOCAL)
ffffffff81bd973d-ffffffff81bd9756: iounmap.part.0.cold (STB_LOCAL)
ffffffff81088d10-ffffffff81088d58: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8108996b)
Location: arch/x86/mm/ioremap.c:439
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - kernel/iomem.c:devm_memremap_release
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_acpi_add
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/cpufreq/pcc-cpufreq.c:pcc_clear_mapping
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff81bcb713-ffffffff81bcb72c: iounmap.cold (STB_LOCAL)
ffffffff81089930-ffffffff810899e1: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81098e0b)
Location: arch/x86/mm/ioremap.c:439
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - kernel/iomem.c:devm_memremap_release
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_acpi_add
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/cpufreq/pcc-cpufreq.c:pcc_clear_mapping
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff81ca0e81-ffffffff81ca0e9a: iounmap.cold (STB_LOCAL)
ffffffff81098dd0-ffffffff81098e81: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810abc3a)
Location: arch/x86/mm/ioremap.c:444
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - kernel/iomem.c:devm_memremap_release
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_acpi_add
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_remove_lock_support
  - drivers/cpufreq/pcc-cpufreq.c:pcc_clear_mapping
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff81e5042e-ffffffff81e50447: iounmap.cold (STB_LOCAL)
ffffffff810abc00-ffffffff810abcc8: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c5670)
Location: arch/x86/mm/ioremap.c:451
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - kernel/iomem.c:devm_memremap_release
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_acpi_add
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_remove_lock_support
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
```
**Symbols:**

```
ffffffff810c5670-ffffffff810c574b: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c8e00)
Location: arch/x86/mm/ioremap.c:456
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - kernel/iomem.c:devm_memremap_release
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_acpi_add
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_remove
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_clean_structure
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_init
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
```
**Symbols:**

```
ffffffff810c8e00-ffffffff810c8edb: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810d1500)
Location: arch/x86/mm/ioremap.c:456
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - kernel/iomem.c:memunmap
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_remove
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_acpi_add
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_remove
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
```
**Symbols:**

```
ffffffff810d1500-ffffffff810d15db: iounmap (STB_GLOBAL)
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
void iounmap(volatile void *io_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/ioremap.c (ffff8000100adf08)
Location: arch/arm64/mm/ioremap.c:72
Inline: False
Direct callers:
  - arch/arm64/kernel/smp_spin_table.c:smp_spin_table_cpu_prepare
  - arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
  - kernel/iomem.c:devm_memremap_release
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_teardown
  - drivers/irqchip/irq-gic.c:gic_teardown
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_teardown
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_init
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_init
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init
  - drivers/irqchip/irq-sni-exiu.c:exiu_acpi_probe
  - drivers/irqchip/irq-sni-exiu.c:exiu_dt_init
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_remove
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/ecam.c:pci_ecam_free
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/amba-clcd.c:clcdfb_remove
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_vram_remove
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/mx3fb.c:mx3fb_remove
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/clk-xgene.c:xgene_devclk_init
  - drivers/clk/clk-xgene.c:xgene_devclk_init
  - drivers/clk/clk-xgene.c:xgene_pmdclk_init
  - drivers/clk/bcm/clk-iproc-armpll.c:iproc_armpll_setup
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_setup
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_setup
  - drivers/clk/mediatek/clk-mt8173.c:mtk_apmixedsys_init
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_common_init
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_init
  - drivers/clk/rockchip/clk-px30.c:px30_clk_init
  - drivers/clk/rockchip/clk-rv1108.c:rv1108_clk_init
  - drivers/clk/rockchip/clk-rk3036.c:rk3036_clk_init
  - drivers/clk/rockchip/clk-rk3128.c:rk3128_common_clk_init
  - drivers/clk/rockchip/clk-rk3188.c:rk3188_common_clk_init
  - drivers/clk/rockchip/clk-rk3228.c:rk3228_clk_init
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init
  - drivers/clk/rockchip/clk-rk3308.c:rk3308_clk_init
  - drivers/clk/rockchip/clk-rk3328.c:rk3328_clk_init
  - drivers/clk/rockchip/clk-rk3368.c:rk3368_clk_init
  - drivers/clk/rockchip/clk-rk3399.c:rk3399_pmu_clk_init
  - drivers/clk/rockchip/clk-rk3399.c:rk3399_clk_init
  - drivers/clk/sunxi/clk-sunxi.c:sunxi_divs_clk_setup
  - drivers/clk/sunxi/clk-sunxi.c:sunxi_divider_clk_setup
  - drivers/clk/sunxi/clk-a10-mod1.c:sun4i_mod1_clk_setup
  - drivers/clk/sunxi/clk-a10-pll2.c:sun4i_pll2_setup
  - drivers/clk/sunxi/clk-a10-ve.c:sun4i_ve_clk_setup
  - drivers/clk/sunxi/clk-a20-gmac.c:sun7i_a20_gmac_clk_setup
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_init
  - drivers/clk/sunxi/clk-sun4i-pll3.c:sun4i_a10_pll3_setup
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_setup
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
  - drivers/clk/sunxi/clk-sun8i-mbus.c:sun8i_a23_mbus_setup
  - drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_of_clk_init_driver
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_setup
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_remove
  - drivers/dma/ipu/ipu_idmac.c:ipu_remove
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_early_init
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/tty/serial/msm_serial.c:msm_release_port
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_remove
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_remove
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/meson/meson_sm.c:meson_sm_probe
  - drivers/clocksource/timer-of.c:timer_of_cleanup
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/timer-rockchip.c:rk_timer_cleanup
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_register
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_find_best_frame
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_get_cntfrq
  - drivers/clocksource/timer-sp804.c:integrator_cp_of_init
  - drivers/clocksource/timer-sp804.c:sp804_of_init
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_remove
```
**Symbols:**

```
ffff8000100adf08-ffff8000100adf58: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iounmap(volatile void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/ioremap.c (c031eef4)
Location: arch/arm/mm/ioremap.c:461
Inline: False
Direct callers:
  - arch/arm/kernel/smp_twd.c:twd_local_timer_of_register
  - arch/arm/kernel/crash_dump.c:copy_oldmem_page
  - arch/arm/kernel/crash_dump.c:copy_oldmem_page
  - arch/arm/mm/iomap.c:pci_iounmap
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_init
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_init
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_init
  - arch/arm/mach-aspeed/platsmp.c:aspeed_g6_smp_prepare_cpus
  - arch/arm/mach-aspeed/platsmp.c:aspeed_g6_boot_secondary
  - arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus
  - arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus
  - arch/arm/mach-exynos/suspend.c:exynos_pmu_irq_init
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platsmp.c:hix5hd2_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hisi_enable_scu_a9
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_setup_boot_addr_wa
  - arch/arm/mach-mvebu/platsmp.c:mv98dx3236_boot_secondary
  - arch/arm/mach-imx/system.c:imx_init_l2cache
  - arch/arm/mach-imx/cpu-imx5.c:imx5_pmu_init
  - arch/arm/mach-imx/cpu-imx5.c:imx5_read_srev_reg
  - arch/arm/mach-imx/anatop.c:imx_init_revision_from_anatop
  - arch/arm/mach-imx/anatop.c:imx_init_revision_from_anatop
  - arch/arm/mach-imx/gpc.c:imx_gpc_init
  - arch/arm/mach-imx/platsmp.c:ls1021a_smp_prepare_cpus
  - arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init
  - arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init
  - arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init
  - arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init
  - arch/arm/mach-imx/mach-imx51.c:imx51_dt_init
  - arch/arm/mach-imx/mach-imx51.c:imx51_dt_init
  - arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init
  - arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_prepare_cpus
  - arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_boot_secondary
  - arch/arm/mach-omap2/timer.c:realtime_counter_init
  - arch/arm/mach-omap2/timer.c:realtime_counter_init
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
  - arch/arm/mach-omap2/omap_phy_internal.c:__omap4430_phy_power_down
  - arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary
  - arch/arm/mach-rockchip/rockchip.c:rockchip_timer_init
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_generic_init
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7778.c:r8a7778_init_irq_dt
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/smp-emev2.c:emev2_smp_prepare_cpus
  - arch/arm/mach-vexpress/dcscb.c:dcscb_init
  - kernel/iomem.c:memunmap
  - fs/pstore/ram_core.c:persistent_ram_free
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_teardown
  - drivers/irqchip/irq-gic.c:gic_teardown
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
  - drivers/irqchip/irq-rda-intc.c:rda8810_intc_init
  - drivers/irqchip/irq-crossbar.c:crossbar_of_init
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_of_init
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_of_init
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
  - drivers/bus/omap_l3_smx.c:omap3_l3_remove
  - drivers/bus/omap_l3_smx.c:omap3_l3_probe
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_remove
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/ecam.c:pci_ecam_free
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/amba-clcd.c:clcdfb_remove
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_vram_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/mx3fb.c:mx3fb_remove
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-milbeaut.c:m10v_cc_of_clk_init_driver
  - drivers/clk/clk-npcm7xx.c:npcm7xx_clk_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/berlin/bg2.c:berlin2_clock_setup
  - drivers/clk/berlin/bg2q.c:berlin2q_clock_setup
  - drivers/clk/berlin/bg2q.c:berlin2q_clock_setup
  - drivers/clk/berlin/bg2q.c:berlin2q_clock_setup
  - drivers/clk/mediatek/clk-mt8173.c:mtk_apmixedsys_init
  - drivers/clk/mvebu/common.c:kirkwood_fix_sscg_deviation
  - drivers/clk/mvebu/common.c:mvebu_clk_gating_setup
  - drivers/clk/mvebu/common.c:mvebu_coreclk_setup
  - drivers/clk/mvebu/common.c:mvebu_coreclk_setup
  - drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup
  - drivers/clk/mvebu/clk-corediv.c:mvebu_corediv_clk_init
  - drivers/clk/mvebu/dove-divider.c:dove_divider_clk_init
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_common_init
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_init
  - drivers/clk/rockchip/clk-px30.c:px30_clk_init
  - drivers/clk/rockchip/clk-rv1108.c:rv1108_clk_init
  - drivers/clk/rockchip/clk-rk3036.c:rk3036_clk_init
  - drivers/clk/rockchip/clk-rk3128.c:rk3128_common_clk_init
  - drivers/clk/rockchip/clk-rk3188.c:rk3188_common_clk_init
  - drivers/clk/rockchip/clk-rk3228.c:rk3228_clk_init
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init
  - drivers/clk/rockchip/clk-rk3308.c:rk3308_clk_init
  - drivers/clk/rockchip/clk-rk3328.c:rk3328_clk_init
  - drivers/clk/rockchip/clk-rk3368.c:rk3368_clk_init
  - drivers/clk/rockchip/clk-rk3399.c:rk3399_pmu_clk_init
  - drivers/clk/rockchip/clk-rk3399.c:rk3399_clk_init
  - drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_init
  - drivers/clk/ti/fapll.c:ti_fapll_setup
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_remove
  - drivers/dma/ipu/ipu_idmac.c:ipu_remove
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/soc/dove/pmu.c:dove_init_pmu
  - drivers/soc/dove/pmu.c:dove_init_pmu
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_fuse_probe
  - drivers/soc/tegra/flowctrl.c:tegra_flowctrl_probe
  - drivers/soc/tegra/pmc.c:tegra186_pmc_setup_irq_polarity
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/tty/serial/msm_serial.c:msm_release_port
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/mfd/sm501.c:sm501_plat_remove
  - drivers/mfd/sm501.c:sm501_pci_remove
  - drivers/mfd/sm501.c:sm501_dev_remove
  - drivers/mfd/sm501.c:sm501_init_dev
  - drivers/mfd/asic3.c:asic3_remove
  - drivers/mfd/asic3.c:asic3_remove
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_remove
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/tc6387xb.c:tc6387xb_remove
  - drivers/mfd/tc6387xb.c:tc6387xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_remove
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_remove
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_remove
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_remove
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
  - drivers/clocksource/timer-of.c:timer_of_cleanup
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_setup
  - drivers/clocksource/renesas-ostm.c:ostm_init
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/timer-rockchip.c:rk_timer_cleanup
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - drivers/clocksource/timer-sp804.c:integrator_cp_of_init
  - drivers/clocksource/timer-sp804.c:sp804_of_init
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_probe
```
**Symbols:**

```
c031eef4-c031ef1c: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iounmap(volatile void *token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/ioremap_64.c (c0000000000899c0)
Location: arch/powerpc/mm/ioremap_64.c:98
Inline: True
Direct callers:
  - arch/powerpc/kernel/rtas_pci.c:rtas_setup_phb
  - arch/powerpc/kernel/eeh.c:eeh_dev_break_write
  - arch/powerpc/kernel/crash_dump.c:copy_oldmem_page
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/sysdev/xive/common.c:xive_cleanup_irq_data
  - arch/powerpc/sysdev/xive/common.c:xive_cleanup_irq_data
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
  - arch/powerpc/platforms/powernv/vas-window.c:unmap_winctx_mmio_bars
  - arch/powerpc/platforms/powernv/vas-window.c:unmap_winctx_mmio_bars
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_map_xsl_regs
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_unmap_xsl_regs
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_unmap_xsl_regs
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_unmap_xsl_regs
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_unmap_xsl_regs
  - kernel/iomem.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/ecam.c:pci_ecam_free
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/gxt4500.c:gxt4500_remove
  - drivers/video/fbdev/gxt4500.c:gxt4500_remove
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/video/fbdev/offb.c:offb_init_fb
  - drivers/video/fbdev/offb.c:offb_init_fb
  - drivers/video/fbdev/offb.c:offb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_rw
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe
```
**Symbols:**

```
c0000000000899c0-c000000000089a40: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/ioremap.c (ffffffe0000b9f30)
Location: arch/riscv/mm/ioremap.c:80
Inline: False
Direct callers:
  - kernel/iomem.c:devm_memremap_release
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-sifive-plic.c:plic_init
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/ecam.c:pci_ecam_free
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/clocksource/timer-of.c:timer_of_cleanup
  - drivers/clocksource/timer-of.c:timer_of_init
```
**Symbols:**

```
ffffffe0000b9f30-ffffffe0000b9f5c: iounmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080aeb)
Location: arch/x86/mm/ioremap.c:437
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/iomem.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_cleanup
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvme/host/pci.c:nvme_remap_bar
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff81080e66-ffffffff81080e7f: iounmap.cold (STB_LOCAL)
ffffffff81080ab0-ffffffff81080b61: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106fa3b)
Location: arch/x86/mm/ioremap.c:437
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/iomem.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_cleanup
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvme/host/pci.c:nvme_remap_bar
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff8106fdb6-ffffffff8106fdcf: iounmap.cold (STB_LOCAL)
ffffffff8106fa00-ffffffff8106fab1: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080a9b)
Location: arch/x86/mm/ioremap.c:437
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/iomem.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_cleanup
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff81080e16-ffffffff81080e2f: iounmap.cold (STB_LOCAL)
ffffffff81080a60-ffffffff81080b11: iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iounmap(volatile void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81082bbb)
Location: arch/x86/mm/ioremap.c:437
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_exit_box
  - arch/x86/kernel/probe_roms.c:pci_unmap_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - kernel/iomem.c:memunmap
  - mm/memory.c:generic_access_phys
  - lib/iomap.c:pci_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_iounmap
  - lib/devres.c:devm_ioremap_release
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_cleanup
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_unmap
```
**Symbols:**

```
ffffffff81082f36-ffffffff81082f4f: iounmap.cold (STB_LOCAL)
ffffffff81082b80-ffffffff81082c31: iounmap (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>volatile void *io_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>volatile void *addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>volatile void *cookie</code>
</li>
<li>
<b>Param removed. </b>
<code>volatile void *addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>volatile void *token</code>
</li>
<li>
<b>Param removed. </b>
<code>volatile void *addr</code>
</li>
</ul>
</details>
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
