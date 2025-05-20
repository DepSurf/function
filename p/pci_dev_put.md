# Function: <code>pci_dev_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81438e50)
Location: drivers/pci/pci-driver.c:1390
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/access.c:pci_vpd_f0_write
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_f0_vpd_link
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:release_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_release
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
```
**Symbols:**

```
ffffffff81438e50-ffffffff81438e6d: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81486688)
Location: drivers/pci/pci-driver.c:1387
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/access.c:pci_vpd_f0_set_size
  - drivers/pci/access.c:pci_vpd_f0_write
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_f0_vpd_link
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_core.c:release_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
```
**Symbols:**

```
ffffffff81484d20-ffffffff81484d3d: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814a7e48)
Location: drivers/pci/pci-driver.c:1396
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/access.c:pci_vpd_f0_set_size
  - drivers/pci/access.c:pci_vpd_f0_write
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_f0_vpd_link
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_core.c:release_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
```
**Symbols:**

```
ffffffff814a64a0-ffffffff814a64bd: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814b1df2)
Location: drivers/pci/pci-driver.c:1414
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/access.c:pci_vpd_f0_set_size
  - drivers/pci/access.c:pci_vpd_f0_write
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_f0_vpd_link
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_core.c:release_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
```
**Symbols:**

```
ffffffff814b0440-ffffffff814b045e: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814f14d7)
Location: drivers/pci/pci-driver.c:1483
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/access.c:pci_vpd_f0_set_size
  - drivers/pci/access.c:pci_vpd_f0_write
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_f0_vpd_link
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_core.c:release_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff814ef980-ffffffff814ef99e: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815216c8)
Location: drivers/pci/pci-driver.c:1504
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_gpu_hda
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:release_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8151f9c0-ffffffff8151f9dd: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815374f8)
Location: drivers/pci/pci-driver.c:1501
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_gpu_hda
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff815357d0-ffffffff815357ed: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81566e51)
Location: drivers/pci/pci-driver.c:1535
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81565180-ffffffff8156519d: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815881b1)
Location: drivers/pci/pci-driver.c:1548
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff815864c0-ffffffff815864dd: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162eef1)
Location: drivers/pci/pci-driver.c:1513
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:setup_ibs_ctl
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arbiter_del_pci_device
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8162d010-ffffffff8162d02d: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816545b1)
Location: drivers/pci/pci-driver.c:1492
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:setup_ibs_ctl
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_hw_error
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arbiter_del_pci_device
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81652700-ffffffff8165271d: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81636f61)
Location: drivers/pci/pci-driver.c:1492
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:pci_notify
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_device_register
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff816351c0-ffffffff816351dd: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a71a1)
Location: drivers/pci/pci-driver.c:1506
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:pci_notify
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_device_register
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff816a5330-ffffffff816a534d: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c9c23)
Location: drivers/pci/pci-driver.c:1535
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/vgaarb.c:pci_notify
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_device_register
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff817c7980-ffffffff817c79a9: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e7653)
Location: drivers/pci/pci-driver.c:1541
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
  - drivers/pci/vgaarb.c:pci_notify
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff818e50c0-ffffffff818e50e9: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8192ac73)
Location: drivers/pci/pci-driver.c:1542
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
  - drivers/pci/vgaarb.c:pci_notify
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_clean_structure
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_init
  - drivers/platform/x86/intel/pmc/mtl.c:mtl_set_device_d3
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81928700-ffffffff81928729: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81973503)
Location: drivers/pci/pci-driver.c:1555
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_base_class
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
  - drivers/pci/vgaarb.c:pci_notify
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81970ef0-ffffffff81970f19: pci_dev_put (STB_GLOBAL)
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
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffff8000106ec59c)
Location: drivers/pci/pci-driver.c:1548
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffff8000106eab08-ffff8000106eab38: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c08878d4)
Location: drivers/pci/pci-driver.c:1548
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
c08859dc-c0885a04: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0000000008681f0)
Location: drivers/pci/pci-driver.c:1548
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_dev_break_write
  - arch/powerpc/kernel/eeh.c:eeh_dev_break_write
  - arch/powerpc/kernel/eeh.c:eeh_dev_check_write
  - arch/powerpc/kernel/eeh.c:eeh_dev_check_write
  - arch/powerpc/kernel/pci_dn.c:pci_remove_device_node_info
  - arch/powerpc/kernel/pci-common.c:pci_phys_mem_access_prot
  - arch/powerpc/kernel/pci_of_scan.c:__of_scan_bus
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
c000000000865de0-c000000000865e20: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffe0004c1648)
Location: drivers/pci/pci-driver.c:1548
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffe0004c0a0e-ffffffe0004c0a3c: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157c041)
Location: drivers/pci/pci-driver.c:1548
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8157a9e0-ffffffff8157a9fd: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8156ae11)
Location: drivers/pci/pci-driver.c:1548
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81569120-ffffffff8156913d: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157bf01)
Location: drivers/pci/pci-driver.c:1548
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8157a210-ffffffff8157a22d: pci_dev_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_dev_put(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815963b1)
Location: drivers/pci/pci-driver.c:1548
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_close
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/proc.c:pci_seq_stop
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_bus
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/iov.c:pci_iov_release
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_release
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/i386.c:pcibios_assign_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81594820-ffffffff8159483d: pci_dev_put (STB_GLOBAL)
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
