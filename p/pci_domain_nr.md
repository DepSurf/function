# Function: <code>pci_domain_nr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810160dd)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019317)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101b3eb)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff81058c5c)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
```
```
In drivers/pci/probe.c (ffffffff8142fafb)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff81438a89)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/search.c (ffffffff8143aa57)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
```
```
In drivers/pci/setup-bus.c (ffffffff81440590)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
```
In drivers/pci/proc.c (ffffffff81441681)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:pci_proc_attach_device
```
```
In drivers/pci/slot.c (ffffffff8144244b)
Location: arch/x86/include/asm/pci.h:35
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff8144b438)
Location: arch/x86/include/asm/pci.h:35
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8144bc9a)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144fa18)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8144ff5a)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81450b1e)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81452c42)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/hotplug-pci.c (ffffffff81453648)
Location: arch/x86/include/asm/pci.h:35
Inline: True
```
```
In drivers/pci/msi.c (ffffffff81455378)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff81456088)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
```
In drivers/acpi/pci_irq.c (ffffffff8148709c)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff814d18fe)
Location: arch/x86/include/asm/pci.h:35
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff814d1d8b)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff814d40e5)
Location: arch/x86/include/asm/pci.h:35
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff81533b94)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff81535620)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/xen.c (ffffffff816f7611)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff816f87cb)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff816fa486)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_read
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pcibios_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101452d)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018717)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a7c1)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff81058fac)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
```
```
In drivers/pci/probe.c (ffffffff8147d630)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff81484900)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/search.c (ffffffff81486c02)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff8148c70a)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff8148de2a)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff8148e2fb)
Location: arch/x86/include/asm/pci.h:35
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff814976c1)
Location: arch/x86/include/asm/pci.h:35
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff81497f3a)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149c1a4)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8149c8fa)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149d332)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149f406)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/hotplug-pci.c (ffffffff8149fee8)
Location: arch/x86/include/asm/pci.h:35
Inline: True
```
```
In drivers/pci/msi.c (ffffffff814a1fb8)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff814a311d)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff814d5ccf)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff815225ee)
Location: arch/x86/include/asm/pci.h:35
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff81522aa4)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff81524e13)
Location: arch/x86/include/asm/pci.h:35
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff815891b6)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158a019)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/xen.c (ffffffff8175c2b1)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff8175d46b)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff8175f560)
Location: arch/x86/include/asm/pci.h:35
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101470d)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810188e7)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ad3c)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff8105bd3c)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
```
```
In drivers/pci/access.c (ffffffff8149a7ea)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8149eba0)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff814a61b5)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/search.c (ffffffff814a83b2)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff814adefa)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff814af61a)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff814afaeb)
Location: arch/x86/include/asm/pci.h:38
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: arch/x86/include/asm/pci.h:38
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff814b9021)
Location: arch/x86/include/asm/pci.h:38
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff814b97ea)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814bdd81)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814be47a)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814beeb2)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c0fb7)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/hotplug-pci.c (ffffffff814c1a68)
Location: arch/x86/include/asm/pci.h:38
Inline: True
```
```
In drivers/pci/msi.c (ffffffff814c3c08)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff814c4d7d)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff814f8327)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff8154eace)
Location: arch/x86/include/asm/pci.h:38
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff8154ef84)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff81551381)
Location: arch/x86/include/asm/pci.h:38
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff815b6876)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b76fd)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/xen.c (ffffffff81788821)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff8178999b)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff8178ba90)
Location: arch/x86/include/asm/pci.h:38
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81012d3d)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81016dd7)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810190e2)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff8105b4ac)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
```
```
In drivers/pci/access.c (ffffffff814a4459)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff814a89e9)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff814aff7d)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/search.c (ffffffff814b233f)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff814b8297)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff814b9ca6)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: arch/x86/include/asm/pci.h:39
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: arch/x86/include/asm/pci.h:39
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff814c3821)
Location: arch/x86/include/asm/pci.h:39
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff814c3fbc)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c8561)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814c8c7f)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c963e)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cb77c)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/hotplug-pci.c (ffffffff814cc048)
Location: arch/x86/include/asm/pci.h:39
Inline: True
```
```
In drivers/pci/msi.c (ffffffff814cdf88)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff814cef9a)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff814d0d81)
Location: arch/x86/include/asm/pci.h:39
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff81507054)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (0)
Location: arch/x86/include/asm/pci.h:39
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff815634e4)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff81565b40)
Location: arch/x86/include/asm/pci.h:39
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff815cc6ba)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d1cae)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/xen.c (ffffffff817a7924)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff817a8a7b)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff817aaa05)
Location: arch/x86/include/asm/pci.h:39
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101354d)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81017657)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101973d)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff814e31ff)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff814e8b9b)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff814ef4ad)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/search.c (ffffffff814f1a2f)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff814f8260)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff814fa0a6)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff81503a61)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff81504205)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81508b14)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8150923f)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81509bee)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8150bcdc)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/msi.c (ffffffff8150e4c8)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff8150f1d5)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff81510fb1)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff815492a1)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (0)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff815c77db)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff815c9ce0)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff8163348e)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff81638a8e)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
```
```
In arch/x86/pci/xen.c (ffffffff8181ec34)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff8181fd1b)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81821eda)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810149cd)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81017ff7)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a3a3)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8151315f)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff815181db)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff8151f5a0)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/search.c (ffffffff81521cbf)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff81528d9c)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff8152ab66)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8152dc07)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_gpu_hda
```
```
In drivers/pci/pcie/aer.c (ffffffff815335ad)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff81535172)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81539a9f)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8153a126)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153b945)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8153c0ea)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153cca6)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8153db7c)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff8153dd93)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8154063b)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/msi.c (ffffffff815433b9)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff81544172)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff81546135)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff8157f401)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff815ffc35)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff8160004b)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff81602562)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff8166e65e)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff81673d8d)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/xen.c (ffffffff81868d5e)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81869f6b)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff8186c19a)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810150cd)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810187c7)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101aa2b)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8152884f)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8152dc5b)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff8152f9cf)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/search.c (ffffffff81537aef)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff8153ec3c)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff815409e6)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81544a57)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_gpu_hda
```
```
In drivers/pci/pcie/aer.c (ffffffff8154a7ad)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c722)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81550ea0)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81551431)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81552e84)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81553568)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815540b6)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81554f2c)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff81555140)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8155770b)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/msi.c (ffffffff8155a739)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff8155b512)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff8155c6d5)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff81597121)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff8161ad05)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff8161b11b)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff8161d652)
Location: arch/x86/include/asm/pci.h:40
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff8168ca8e)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff8169231d)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693de5)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
```
In arch/x86/pci/xen.c (ffffffff81888dde)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81889feb)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff8188c27a)
Location: arch/x86/include/asm/pci.h:40
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016bde)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019d96)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c46b)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8155861b)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8155c3db)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff8155f131)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/search.c (ffffffff81567490)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff8156e0cf)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff815702e8)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81575128)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff8157b6bf)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c360)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8158101f)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81581399)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81581c83)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8158364c)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81584907)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8158504e)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff8158524d)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81587744)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/msi.c (ffffffff8158a829)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff8158b823)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff8158ca05)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff815c82d3)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff8164ea62)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff8164ee03)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff81650865)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816c44de)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ca2a4)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cc6e5)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
```
In arch/x86/pci/xen.c (ffffffff818d36ae)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff818d4641)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff818d6bca)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101758e)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a716)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cdeb)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d5a7)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/access.c (ffffffff81579c16)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8157d4ab)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81580271)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/search.c (ffffffff815887e0)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff8158f0af)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff815913c8)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff815967c8)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff8159d135)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff8159ddc0)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a2a1f)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815a2e99)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3713)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815a502c)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815a62e7)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff815a6a2e)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff815a6c2d)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a9104)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/msi.c (ffffffff815ac1a9)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff815ad3d3)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff815ae625)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff815e94f3)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff81670ed5)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff816713b3)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff81672e05)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816e742e)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ed274)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/iommu/intel-pasid.c (ffffffff816eff35)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d6299)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
```
```
In arch/x86/pci/xen.c (ffffffff81906088)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff819069c1)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81908f4a)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
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
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101c1a6)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101eb5b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810746d7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/access.c (ffffffff8161ec83)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff81622a9b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81625628)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff8162f490)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff81636b1f)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/pcie/aer.c (ffffffff8163ce21)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff8163d8a8)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/proc.c (ffffffff8163f6d8)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff8163fdcd)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81644e98)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8164b40e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8164ba17)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c0e8)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8164dc9d)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8164eef7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8164f73c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff8164f93d)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81651d87)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/msi.c (ffffffff816552a9)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff81656bf3)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff81657875)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff81694ed0)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/xen/pci.c (ffffffff817215b5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81721ab3)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff817234f4)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179dc93)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a5314)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a7465)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3189)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
```
```
In arch/x86/pci/xen.c (ffffffff81bb600e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81bb70b1)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81bb985a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101c736)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101f897)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_show
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075157)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/access.c (ffffffff81bf6e37)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8164968b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff8164afc8)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff81654b20)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff8165bbdf)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi.c (ffffffff8165d495)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff81660295)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff81bf9172)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff81663f38)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/proc.c (ffffffff81665b28)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff816661fd)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8166b2a8)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81bfbdbe)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8166fd97)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670438)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81bfc4f6)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81bfc948)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81bfd013)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff81672ddd)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81674747)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff816771b3)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff81677cc5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff816b2120)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/xen/pci.c (ffffffff8173e285)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff8173e773)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff81740149)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ab9da)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b276e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b332b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b1e39)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
```
```
In arch/x86/pci/xen.c (ffffffff81bcb1b0)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81bcc141)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81bce14a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101dbe6)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81020ebb)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103308c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075bf7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/access.c (ffffffff81be8ca6)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8162c24b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff8162dbcc)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff816374e5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff8163e17f)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi.c (ffffffff8163f8ec)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff81642785)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff81beafa2)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff816463a8)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/proc.c (ffffffff816480c8)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff8164879d)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8164d598)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81bedc8d)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81652297)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81652b23)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81bee3e1)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81bee833)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81beeeeb)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff816552dd)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81656c74)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff8165976f)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff8165a335)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff816944c5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/xen/pci.c (ffffffff81721d25)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81722294)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff81723b99)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178e83a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179565e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/iommu/intel/pasid.c (ffffffff8179637b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895269)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
```
```
In arch/x86/pci/xen.c (ffffffff81bbeaf7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81bbfb87)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81bc1b0a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81020ce6)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024a9b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103822c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81083177)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/access.c (ffffffff81ce3082)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8169b71b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff8169d2bc)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff816a775d)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff816aecdf)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi.c (ffffffff816b095c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff816b3485)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff816b5fa7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff816b7c18)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/proc.c (ffffffff816b9ad8)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff816ba19d)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff816bf358)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81ce8a54)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff816c3fd7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c48a0)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81ce92f4)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81ce97a6)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81ce9f51)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff816c718b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c8c06)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff816cba6f)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff816cc675)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff8170a1d5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/acpi/viot.c (ffffffff8176cd55)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_pci_dev_iommu_init
```
```
In drivers/xen/pci.c (ffffffff817a0b63)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff817a10e4)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff817a2a63)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff818160ca)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181d4d2)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e30b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81928969)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode
```
```
In arch/x86/pci/xen.c (ffffffff81c8ea1f)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81c8fae7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81c9211a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/pci.h:44
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
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810282a3)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e503)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81092ff3)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/access.c (ffffffff81ea9b6f)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff817bceeb)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff817bf40b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff817ca193)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff817d216d)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi/irqdomain.c (ffffffff817d5625)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff817d6861)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff817d99d7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff817dbff8)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/pcie/edr.c (ffffffff81ead766)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/proc.c (ffffffff817de36d)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff817deaec)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff817e4db5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81eafabf)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff817e9b51)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817ea4d9)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81eb0376)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81eb089b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81eb100e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff817ed138)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817eee69)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff817f210e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff817f2e65)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff81838711)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/viot.c (ffffffff818a1d85)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_pci_dev_iommu_init
```
```
In drivers/xen/pci.c (ffffffff818dae13)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff818daf98)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff818dcd27)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff81956f8a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195cc57)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7e82d)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode
```
```
In arch/x86/pci/xen.c (ffffffff81e3e3db)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff81e3eb27)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81e4175a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/pci.h:44
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
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102d34d)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810473e3)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a8343)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/access.c (ffffffff818d2922)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff818d8e8b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff818db9cb)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff818e7c43)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff818f25c9)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi/irqdomain.c (ffffffff818f6645)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff818f7df1)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff818fb2cc)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff818fde59)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/pcie/edr.c (ffffffff818ffd11)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/proc.c (ffffffff81900efd)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff8190176c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81909775)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190ef9c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8190fb61)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819105e9)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8191234c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81912ff3)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8191422b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff819143b8)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8191710e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff8191a692)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff8191b5a5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff8191d440)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/acpi/pci_irq.c (ffffffff8196daa1)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/viot.c (ffffffff819eb575)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_pci_dev_iommu_init
```
```
In drivers/xen/pci.c (ffffffff81a2ddf6)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81a2df98)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff81a300c2)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab5f80)
Location: arch/x86/include/asm/pci.h:44
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
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac4805)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In arch/x86/pci/xen.c (ffffffff82017b5b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff82018727)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff8201bd8a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/pci.h:44
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81029357)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e871)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_update_device_location
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047763)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab5b3)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/access.c (ffffffff81915922)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8191c1cb)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff8191ea9b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff8192b25d)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff819359e9)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81939aa5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff8193b251)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff8193e7b5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff81941309)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/pcie/edr.c (ffffffff81943281)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/proc.c (ffffffff819444bd)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff81944d2c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8194cdf5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8195260c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8195327f)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81953d09)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff819559dc)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8195666e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8195788b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff81957a0e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195a70e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff8195dcc2)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff8195ebb5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff81960a00)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/acpi/pci_irq.c (ffffffff819b3fd1)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/viot.c (ffffffff81a33cac)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_pci_dev_iommu_init
```
```
In drivers/xen/pci.c (ffffffff81a7759a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81a77748)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff81a798d2)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b02453)
Location: arch/x86/include/asm/pci.h:44
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
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b111a5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In arch/x86/pci/xen.c (ffffffff82097f4b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff82098cf7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff8209c42a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/pci.h:44
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
In arch/x86/events/intel/uncore_snb.c (ffffffff8102f4b7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81034931)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_update_device_location
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104dea3)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b2423)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/access.c (ffffffff8195d892)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff819645fb)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81966bab)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/search.c (ffffffff81973add)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff8197e799)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81982905)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/rcec.c (ffffffff819840e1)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:walk_rcec
```
```
In drivers/pci/pcie/aer.c (ffffffff819879bd)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a569)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
```
```
In drivers/pci/pcie/edr.c (ffffffff8198c551)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/proc.c (ffffffff8198d7bd)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (ffffffff8198e05c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff819960b5)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199ba9c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8199c70f)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d199)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8199eec7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8199fb8e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff819a0dfb)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff819a0f7e)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a3d0c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff819a7322)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff819a8215)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff819aa11a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/acpi/pci_irq.c (ffffffff819fe4b0)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/acpi/viot.c (ffffffff81a7f11c)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_pci_dev_iommu_init
```
```
In drivers/xen/pci.c (ffffffff81ac97aa)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81ac9958)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In drivers/xen/platform-pci.c (ffffffff81acbd42)
Location: arch/x86/include/asm/pci.h:44
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b55e6e)
Location: arch/x86/include/asm/pci.h:44
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
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b63869)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:device_lookup_iommu
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c96f9f)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_show_fdinfo
```
```
In drivers/gpu/drm/drm_pci.c (ffffffff81cb9cef)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_pci.c:drm_pci_set_busid
```
```
In arch/x86/pci/xen.c (ffffffff8216f42b)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff821701d7)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff82173c0a)
Location: arch/x86/include/asm/pci.h:44
Inline: True
Inline callers:
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/slot.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/pci-label.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-al.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/acpi/pci_irq.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/acpi/arm64/iort.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/xen/pci.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/xen/dbgp.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c08774d8)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (c087c9c4)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (c087e9e0)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/search.c (c0887ffc)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (c088ee80)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (c0891158)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/quirks.c (c0896548)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/pcie/aer.c (c089c52c)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (c089d210)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/msi.c (c089e280)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_set_desc
```
```
In drivers/pci/iov.c (c08a19b4)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (c08a2d80)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:find_smbios_instance_string
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_domain_nr(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/pci-common.c (c00000000006c720)
Location: arch/powerpc/kernel/pci-common.c:324
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_finish_adding_to_bus
  - arch/powerpc/kernel/pci-common.c:pcibios_resource_survey
  - arch/powerpc/kernel/pci-common.c:pcibios_resource_survey
  - arch/powerpc/kernel/pci-common.c:pcibios_resource_survey
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_bus_resources
  - arch/powerpc/kernel/pci-common.c:pci_mmap_legacy_page_range
  - arch/powerpc/kernel/pci-common.c:pci_mmap_legacy_page_range
Direct callers:
  - arch/powerpc/kernel/pci-hotplug.c:pci_hp_remove_devices
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_bus_PE
  - arch/powerpc/platforms/powernv/pci-ioda.c:pe_level_printk
  - arch/powerpc/platforms/powernv/pci-ioda.c:pe_level_printk
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_bridge_reset
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_bridge_reset
  - arch/powerpc/platforms/powernv/ocxl.c:find_link
  - arch/powerpc/platforms/powernv/ocxl.c:find_link
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_dev_setup_pSeriesLP
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_bus_setup_pSeriesLP
  - arch/powerpc/platforms/pseries/pci.c:pseries_set_pe_num
  - arch/powerpc/platforms/pseries/pci_dlpar.c:remove_phb_dynamic
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
```
**Symbols:**

```
c00000000006bb80-c00000000006bb94: pci_domain_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3dd6)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffe0004b8992)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffe0004ba4b8)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/search.c (ffffffe0004c1bde)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffe0004c7550)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffe0004c8f1a)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/quirks.c (ffffffe0004cd8cc)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffe0004d333a)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffe0004d3eb4)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d7e8a)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffe0004d83a2)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8ae8)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004da2a4)
Location: include/linux/pci.h:1602
Inline: True
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004dab50)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffe0004db87a)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffe0004db9fe)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/msi.c (ffffffe0004dd470)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_set_desc
```
```
In drivers/pci/iov.c (ffffffe0004e0518)
Location: include/linux/pci.h:1602
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101758e)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a716)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cdeb)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8156e136)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff815719cb)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81574791)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/search.c (ffffffff8157c670)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff81582f2f)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff81585258)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8158a658)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff81590c05)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff815915c0)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8159622f)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815966a9)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81596f23)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8159883c)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81599af7)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8159a23e)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff8159a43d)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159c8f5)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/msi.c (ffffffff8159f979)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff815a0ba3)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff815a1de5)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff815da533)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff81636f95)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81637473)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff81638af5)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816acf0e)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b29e4)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b5725)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
```
In arch/x86/pci/xen.c (ffffffff818a5448)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff818a5d81)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff818a830a)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810169be)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019e76)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c4db)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8155c896)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8156012b)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81562ef1)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/search.c (ffffffff8156b440)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff81571d0f)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff81574028)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81579198)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff8157fb05)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff815808b4)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815853bf)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81585839)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815860b3)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815879cc)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81588c87)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff815893ce)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff815895cd)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158ba85)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/msi.c (ffffffff8158eb09)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff8158fd33)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff81590f85)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff815c4153)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/iommu/dmar.c (ffffffff8168a86e)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff816906a4)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693365)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81780349)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
```
```
In arch/x86/pci/fixup.c (ffffffff818608b1)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff81862d87)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101754e)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a6d6)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cdab)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8156d966)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff815711fb)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81573fc1)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/search.c (ffffffff8157c530)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff81582dff)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff81585118)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8158a518)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff81590e85)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff81591b10)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8159676f)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81596be9)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597463)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598d7c)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8159a037)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8159a77e)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff8159a97d)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159ce54)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/msi.c (ffffffff8159fef9)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff815a1123)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff815a2375)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff815dd7d3)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff81664d15)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff816651f3)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff81666c45)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816db0ee)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e0f34)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e3bf5)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cb119)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
```
```
In arch/x86/pci/xen.c (ffffffff818f6aa8)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff818f73e1)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff818f996a)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017790)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a916)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cdfb)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106ec77)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/access.c (ffffffff81587e46)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
```
```
In drivers/pci/probe.c (ffffffff8158b6db)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_sort_bf_cmp
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff8158e4a1)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/search.c (ffffffff815969e0)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/search.c:pci_find_bus
```
```
In drivers/pci/setup-bus.c (ffffffff8159d2af)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/proc.c (ffffffff8159f5c8)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
```
In drivers/pci/slot.c (0)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff815a49c8)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff815ab335)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_port_info
```
```
In drivers/pci/pcie/pme.c (ffffffff815ac151)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b0bea)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815b1069)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b18a3)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815b31bc)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815b4477)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff815b4bbe)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff815b4dbd)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b7284)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/msi.c (ffffffff815ba329)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/pci/iov.c (ffffffff815bb553)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/pci-label.c (ffffffff815bc775)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff815f7693)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff8167f2c5)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff8167f7a3)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In drivers/xen/platform-pci.c (ffffffff816811f5)
Location: arch/x86/include/asm/pci.h:41
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816f56ac)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fb527)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fe2a5)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e53b9)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode
```
```
In arch/x86/pci/xen.c (ffffffff819177b8)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff819184e1)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
```
```
In arch/x86/pci/common.c (ffffffff8191aaca)
Location: arch/x86/include/asm/pci.h:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pcibios_add_device
  - arch/x86/pci/common.c:pci_write
  - arch/x86/pci/common.c:pci_read
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
