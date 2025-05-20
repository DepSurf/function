# Function: <code>to_pci_sysdata</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101911e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101c1a6)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101eb5b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/kernel/quirks.c (ffffffff8103c14d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810746d7)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/access.c (ffffffff8161ec83)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff81622a9b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci.c (ffffffff81625628)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff8162f490)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff8162fc15)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
```
In drivers/pci/setup-bus.c (ffffffff81636b1f)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/pcie/aer.c (ffffffff8163ce21)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff8163d8a8)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/proc.c (ffffffff8163f6d8)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff8163fdcd)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81644e98)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8164b40e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8164ba17)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c0e8)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8164dc9d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8164eef7)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8164f73c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff8164f93d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81651d87)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/msi.c (ffffffff816552a9)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff81656bf3)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff81657875)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff81694ed0)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/xen/pci.c (ffffffff817215b5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81721ab3)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff817234f4)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179dc93)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a5314)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a7465)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3189)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
```
```
In arch/x86/pci/xen.c (ffffffff81bb600e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81bb6c6a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81bb99c5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101989e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101c736)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101f897)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_show
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/kernel/quirks.c (ffffffff8103c8ad)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075157)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/access.c (ffffffff81bf6e37)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8164968b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci.c (ffffffff8164afc8)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff81654b20)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff816552a5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
```
In drivers/pci/setup-bus.c (ffffffff8165bbdf)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi.c (ffffffff8165d495)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff81660295)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff81bf9172)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff81663f38)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/proc.c (ffffffff81665b28)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff816661fd)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8166b2a8)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81bfbdbe)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8166fd97)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670438)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81bfc4f6)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81bfc948)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81bfd013)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff81672ddd)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81674747)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff816771b3)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff81677cc5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff816b2120)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/xen/pci.c (ffffffff8173e285)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff8173e773)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff81740149)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ab9da)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b276e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b332b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b1e39)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
```
```
In arch/x86/pci/xen.c (ffffffff81bcb1b0)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81bcbcfa)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81bce2d5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101949d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101dbe6)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81020ea4)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810221f8)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103308c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/quirks.c (ffffffff8103e0dd)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075bf7)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/access.c (ffffffff81be8ca6)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8162c24b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci.c (ffffffff8162dbcc)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff816374e5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff81637ed5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
```
In drivers/pci/setup-bus.c (ffffffff8163e17f)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi.c (ffffffff8163f8ec)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff81642785)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff81beafa2)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff816463a8)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/proc.c (ffffffff816480c8)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff8164879d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8164d598)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81bedc8d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81652297)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81652b23)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81bee3e1)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81bee833)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81beeeeb)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff816552dd)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81656c74)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff8165976f)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff8165a335)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff816944c5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/xen/pci.c (ffffffff81721d25)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81722294)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff81723b99)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178e83a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179565e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/iommu/intel/pasid.c (ffffffff8179637b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895269)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
```
```
In arch/x86/pci/xen.c (ffffffff81bbeaf7)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81bbf67a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81bc1c95)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101becd)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81020ce6)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024a84)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81025d68)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103822c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/quirks.c (ffffffff81043d8d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81083177)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/access.c (ffffffff81ce3082)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8169b71b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci.c (ffffffff8169d2bc)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff816a775d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a8145)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
```
In drivers/pci/setup-bus.c (ffffffff816aecdf)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi.c (ffffffff816b095c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff816b3485)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff816b5fa7)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff816b7c18)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/proc.c (ffffffff816b9ad8)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff816ba19d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff816bf358)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81ce8a54)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff816c3fd7)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c48a0)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81ce92f4)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81ce97a6)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81ce9f51)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff816c718b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c8c06)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff816cba6f)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff816cc675)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff8170a1d5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/acpi/viot.c (ffffffff8176cd55)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_pci_dev_iommu_init
```
```
In drivers/xen/pci.c (ffffffff817a0b63)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff817a10e4)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff817a2a63)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff818160ca)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181d4d2)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e30b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81928969)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode
```
```
In arch/x86/pci/xen.c (ffffffff81c8ea1f)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81c8f5ea)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81c922a5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101ff52)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81024217)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810282a3)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029dc9)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e503)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/quirks.c (ffffffff8104bf04)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81092ff3)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/access.c (ffffffff81ea9b6f)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff817bceeb)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci.c (ffffffff817bf40b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff817ca193)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cace5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
```
In drivers/pci/setup-bus.c (ffffffff817d216d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi/irqdomain.c (ffffffff817d5625)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff817d6861)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff817d99d7)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff817dbff8)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/pcie/edr.c (ffffffff81ead766)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/proc.c (ffffffff817de36d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff817deaec)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff817e4db5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81eafabf)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff817e9b51)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817ea4d9)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81eb0376)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81eb089b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81eb100e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff817ed138)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817eee69)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff817f210e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff817f2e65)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff81838711)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/viot.c (ffffffff818a1d85)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_pci_dev_iommu_init
```
```
In drivers/xen/pci.c (ffffffff818dae13)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff818daf98)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff818dcd27)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff81956f8a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195cc57)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7e82d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode
```
```
In arch/x86/pci/xen.c (ffffffff81e3e3db)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81e3e57a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81e41925)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_device_add
  - arch/x86/pci/common.c:pcibios_device_add
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff83e69e47)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81029327)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102d34d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030889)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810473e3)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/quirks.c (ffffffff810581e4)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a8343)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/access.c (ffffffff818d2922)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff818d8e8b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci.c (ffffffff818db9cb)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff818e7c43)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e8885)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
```
In drivers/pci/setup-bus.c (ffffffff818f25c9)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi/irqdomain.c (ffffffff818f6645)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff818f7df1)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff818fb2cc)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff818fde59)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/pcie/edr.c (ffffffff818ffd11)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/proc.c (ffffffff81900efd)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff8190176c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81909775)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190ef9c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8190fb61)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819105e9)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8191234c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81912ff3)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8191422b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff819143b8)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8191710e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff8191a692)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff8191b5a5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff8191d440)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/acpi/pci_irq.c (ffffffff8196daa1)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/viot.c (ffffffff819eb575)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_pci_dev_iommu_init
```
```
In drivers/xen/pci.c (ffffffff81a2ddf6)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81a2df98)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff81a300c2)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab5f80)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:check_device
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abde7a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac4805)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In arch/x86/pci/xen.c (ffffffff82017b5b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff82017d4a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff8201bfa5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_device_add
  - arch/x86/pci/common.c:pcibios_device_add
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8368a7d7)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81029357)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e871)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_update_device_location
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff8103099e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047763)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/quirks.c (ffffffff81059384)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab5b3)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/access.c (ffffffff81915922)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8191c1cb)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci.c (ffffffff8191ea9b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff8192b25d)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192be95)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
```
In drivers/pci/setup-bus.c (ffffffff819359e9)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81939aa5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff8193b251)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff8193e7b5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff81941309)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/pcie/edr.c (ffffffff81943281)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/proc.c (ffffffff819444bd)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff81944d2c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8194cdf5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8195260c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8195327f)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81953d09)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff819559dc)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8195666e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8195788b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff81957a0e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195a70e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff8195dcc2)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff8195ebb5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff81960a00)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/acpi/pci_irq.c (ffffffff819b3fd1)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/viot.c (ffffffff81a33cac)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_pci_dev_iommu_init
```
```
In drivers/xen/pci.c (ffffffff81a7759a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81a77748)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff81a798d2)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b02453)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0a80a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b111a5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In arch/x86/pci/xen.c (ffffffff82097f4b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff8209813a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff8209c645)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_device_add
  - arch/x86/pci/common.c:pcibios_device_add
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff838ba397)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102f4b7)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81034931)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_update_device_location
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036c6e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104dea3)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/quirks.c (ffffffff810605a4)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b2423)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/access.c (ffffffff8195d892)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff819645fb)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci.c (ffffffff81966bab)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff81973add)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff81974785)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
```
In drivers/pci/setup-bus.c (ffffffff8197e799)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81982905)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff819840e1)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff819879bd)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a569)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/pcie/edr.c (ffffffff8198c551)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/proc.c (ffffffff8198d7bd)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff8198e05c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff819960b5)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199ba9c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8199c70f)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d199)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8199eec7)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8199fb8e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff819a0dfb)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff819a0f7e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a3d0c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff819a7322)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff819a8215)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff819aa11a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/acpi/pci_irq.c (ffffffff819fe4b0)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/acpi/viot.c (ffffffff81a7f11c)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_pci_dev_iommu_init
```
```
In drivers/xen/pci.c (ffffffff81ac97aa)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81ac9958)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff81acbd42)
Location: arch/x86/include/asm/pci.h:36
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b55e6e)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5e85a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b63869)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:device_lookup_iommu
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c96f9f)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_show_fdinfo
```
```
In drivers/gpu/drm/drm_pci.c (ffffffff81cb9cef)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_pci.c:drm_pci_set_busid
```
```
In arch/x86/pci/xen.c (ffffffff8216f42b)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff8216f61a)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff82173e25)
Location: arch/x86/include/asm/pci.h:36
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_device_add
  - arch/x86/pci/common.c:pcibios_device_add
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
