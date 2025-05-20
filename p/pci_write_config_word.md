# Function: <code>pci_write_config_word</code>

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
In drivers/pci/access.c (ffffffff8142e34a)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/probe.c (ffffffff8142fd7e)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff81433c7e)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/pci-driver.c (ffffffff81439b46)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/setup-res.c (ffffffff8143d53e)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_enable_resources
```
```
In drivers/pci/setup-bus.c (ffffffff8143e2cd)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
```
In drivers/pci/vc.c (ffffffff81440d3f)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (ffffffff81443ea8)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_xio2000a
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81450099)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/msi.c (ffffffff814538be)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_enable_msi_range
  - drivers/pci/msi.c:pci_enable_msi_range
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
```
In drivers/pci/ats.c (ffffffff81455874)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_enable_pri
```
```
In drivers/pci/iov.c (ffffffff81456440)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
```
```
In drivers/char/agp/generic.c (ffffffff8151d945)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/isoch.c (ffffffff8151e5c3)
Location: include/linux/pci.h:923
Inline: True
```
```
In drivers/char/agp/intel-agp.c (ffffffff81520218)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815215f6)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
```
```
In drivers/iommu/amd_iommu.c (ffffffff815305a8)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
```
In drivers/ata/ata_piix.c (ffffffff815e2c6e)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/ata/pata_sis.c (ffffffff815e3e27)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
```
```
In drivers/ata/ata_generic.c (ffffffff815e4b5e)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8162fae0)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816455c6)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
```
```
In drivers/hwmon/hwmon.c (ffffffff81fb2c87)
Location: include/linux/pci.h:923
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/fixup.c (ffffffff816f8aad)
Location: include/linux/pci.h:923
Inline: True
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
In drivers/pci/access.c (ffffffff8147991a)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/probe.c (ffffffff8147cdb1)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff81484a48)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
```
```
In drivers/pci/pci-driver.c (ffffffff81485a11)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/setup-res.c (ffffffff814899c1)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8148bbd2)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
```
```
In drivers/pci/vc.c (ffffffff8148d1dd)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (ffffffff8148fd78)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_xio2000a
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814981f8)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_remove
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8149c869)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/msi.c (ffffffff814a132f)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
```
```
In drivers/pci/ats.c (ffffffff814a252b)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/pci/iov.c (ffffffff814a3761)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/char/agp/generic.c (ffffffff81570721)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/isoch.c (ffffffff81571415)
Location: include/linux/pci.h:934
Inline: True
```
```
In drivers/char/agp/intel-agp.c (ffffffff81573261)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81574486)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
```
```
In drivers/iommu/amd_iommu.c (ffffffff815851dd)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
```
In drivers/ata/ata_piix.c (ffffffff8163d395)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
```
```
In drivers/ata/pata_sis.c (ffffffff8163dc29)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
```
```
In drivers/ata/ata_generic.c (ffffffff8163e885)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81691046)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aa63b)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
```
```
In drivers/hwmon/hwmon.c (ffffffff81fdf854)
Location: include/linux/pci.h:934
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/fixup.c (ffffffff8175d7a4)
Location: include/linux/pci.h:934
Inline: True
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
In drivers/pci/access.c (ffffffff8149adaa)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/probe.c (ffffffff8149e311)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff814a5f51)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
```
```
In drivers/pci/pci-driver.c (ffffffff814a71d1)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/setup-res.c (ffffffff814ab1b1)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814ad3c2)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
```
```
In drivers/pci/vc.c (ffffffff814ae9cd)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (ffffffff814b15c8)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_xio2000a
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814b9aa8)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_remove
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814be3e9)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/msi.c (ffffffff814c2f0d)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
```
```
In drivers/pci/ats.c (ffffffff814c417b)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/pci/iov.c (ffffffff814c53c1)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/char/agp/generic.c (ffffffff8159cde1)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/isoch.c (ffffffff8159dad5)
Location: include/linux/pci.h:964
Inline: True
```
```
In drivers/char/agp/intel-agp.c (ffffffff8159f8d1)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a0b06)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b22fb)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
```
In drivers/ata/ata_piix.c (ffffffff8166e415)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
```
```
In drivers/ata/pata_sis.c (ffffffff8166ec99)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
```
```
In drivers/ata/ata_generic.c (ffffffff8166f8fe)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bf0f6)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d877b)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
```
```
In drivers/hwmon/hwmon.c (ffffffff8201d4bf)
Location: include/linux/pci.h:964
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/fixup.c (ffffffff81789cd4)
Location: include/linux/pci.h:964
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4b37)
Location: drivers/pci/access.c:942
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/pcie-dpc.c:dpc_remove
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff814a4990-ffffffff814a49c6: pci_write_config_word.part.12 (STB_LOCAL)
ffffffff814a49d0-ffffffff814a49f5: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3917)
Location: drivers/pci/access.c:942
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/pcie-dpc.c:dpc_remove
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff814e3760-ffffffff814e379c: pci_write_config_word.part.12 (STB_LOCAL)
ffffffff814e37a0-ffffffff814e37c5: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8151331a)
Location: drivers/pci/access.c:575
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff81513000-ffffffff81513050: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528a6e)
Location: drivers/pci/access.c:575
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff81528730-ffffffff8152875d: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815579c0)
Location: drivers/pci/access.c:575
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:program_hpp_type0
  - drivers/pci/probe.c:program_hpp_type0
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff815579c0-ffffffff815579ef: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578ff0)
Location: drivers/pci/access.c:566
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff81578ff0-ffffffff8157901f: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e50d)
Location: drivers/pci/access.c:562
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_msi_setup_pci_dev
  - drivers/pci/probe.c:pci_msi_setup_pci_dev
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_disable_acs_redir
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_restore_pasid_state
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_restore_ats_state
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff8161e000-ffffffff8161e02f: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644d2c)
Location: drivers/pci/access.c:562
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_disable_acs_redir
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi.c:pci_msix_init
  - drivers/pci/msi.c:pci_msi_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_restore_pasid_state
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_restore_ats_state
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff81644820-ffffffff8164484f: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816279cc)
Location: drivers/pci/access.c:562
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi.c:pci_msix_init
  - drivers/pci/msi.c:pci_msi_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_restore_pasid_state
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_restore_ats_state
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff816275a0-ffffffff816275cf: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816972cc)
Location: drivers/pci/access.c:562
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi.c:pci_msix_init
  - drivers/pci/msi.c:pci_msi_init
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_restore_pasid_state
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_restore_ats_state
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff81696df0-ffffffff81696e1f: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b7e30)
Location: drivers/pci/access.c:567
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_set_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:__pci_pme_active
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:quirk_disable_pxb
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_restore_pasid_state
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_restore_ats_state
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_memory_lock_and_enable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff817b7e30-ffffffff817b7e75: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d26f0)
Location: drivers/pci/access.c:573
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_set_mwi
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:__pci_pme_active
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:quirk_disable_pxb
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_restore_pasid_state
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_restore_ats_state
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff818d26f0-ffffffff818d2735: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff819156f0)
Location: drivers/pci/access.c:587
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_set_mwi
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:__pci_pme_active
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:quirk_disable_pxb
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_restore_pasid_state
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_restore_ats_state
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff819156f0-ffffffff81915735: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195d660)
Location: drivers/pci/access.c:585
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_set_mwi
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:__pci_pme_active
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:quirk_disable_pxb
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_restore_pasid_state
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_restore_ats_state
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff8195d660-ffffffff8195d6a5: pci_write_config_word (STB_GLOBAL)
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
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106dbe14)
Location: drivers/pci/access.c:566
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffff8000106dbd58-ffff8000106dbdc0: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877e44)
Location: drivers/pci/access.c:566
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - arch/arm/kernel/bios32.c:pcibios_fixup_bus
  - arch/arm/kernel/bios32.c:pcibios_fixup_bus
  - arch/arm/kernel/bios32.c:pcibios_fixup_bus
  - arch/arm/kernel/bios32.c:pci_fixup_83c553
  - arch/arm/kernel/bios32.c:pci_fixup_83c553
  - arch/arm/kernel/bios32.c:pcibios_bus_report_status
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
c08772f8-c0877338: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852970)
Location: drivers/pci/access.c:566
Inline: True
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_dev_break_write
  - arch/powerpc/kernel/eeh.c:eeh_dev_break_write
  - arch/powerpc/kernel/eeh.c:eeh_disable_and_save_dev_state
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_restore_ats_state
  - drivers/pci/ats.c:pci_restore_ats_state
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
c000000000852970-c0000000008529b8: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3f78)
Location: drivers/pci/access.c:566
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_restore_ats_state
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffe0004b3c68-ffffffe0004b3cb2: pci_write_config_word (STB_GLOBAL)
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
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d510)
Location: drivers/pci/access.c:566
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff8156d510-ffffffff8156d53f: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155bc80)
Location: drivers/pci/access.c:566
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff8155bc80-ffffffff8155bcaf: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156cd40)
Location: drivers/pci/access.c:566
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff8156cd40-ffffffff8156cd6f: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_word(const struct pci_dev *dev, int where, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587240)
Location: drivers/pci/access.c:566
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffff81587240-ffffffff8158726f: pci_write_config_word (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
