# Function: <code>pci_read_config_word</code>

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
In drivers/pci/access.c (ffffffff8142e44b)
Location: include/linux/pci.h:910
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8142fd3b)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff81433c46)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/setup-res.c (ffffffff8143d525)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_enable_resources
```
```
In drivers/pci/setup-bus.c (ffffffff8143e310)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
```
In drivers/pci/vc.c (ffffffff81440f37)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (ffffffff81443b28)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81450080)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/msi.c (ffffffff814537d9)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_enable_msi_range
  - drivers/pci/msi.c:pci_enable_msi_range
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
```
```
In drivers/pci/ats.c (ffffffff81455941)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_pri
```
```
In drivers/pci/iov.c (ffffffff81455fcd)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
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
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150a441)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/char/agp/generic.c (ffffffff8151d863)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
```
```
In drivers/char/agp/isoch.c (ffffffff8151e593)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8151fc8b)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81520126)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815215d6)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff8152314a)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
```
```
In drivers/iommu/amd_iommu.c (ffffffff81530589)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
```
In drivers/iommu/intel-iommu.c (ffffffff81536e26)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81540322)
Location: include/linux/pci.h:910
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff815c90c5)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:pci_test_config_bits
```
```
In drivers/ata/ata_piix.c (ffffffff815e2c43)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/ata/pata_sis.c (ffffffff815e3c8a)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
```
```
In drivers/ata/ata_generic.c (ffffffff815e4a73)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8162faa6)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8163cd38)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/hwmon/hwmon.c (ffffffff81fb2c52)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/i386.c (ffffffff816f6159)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
```
In arch/x86/pci/fixup.c (ffffffff816f886a)
Location: include/linux/pci.h:910
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/access.c (ffffffff81479a0b)
Location: include/linux/pci.h:921
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8147cd96)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff81484a2e)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
```
```
In drivers/pci/setup-res.c (ffffffff81489876)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_update_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8148b877)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
```
In drivers/pci/vc.c (ffffffff8148d1c1)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (ffffffff81493008)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814981bc)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_remove
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8149c850)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/msi.c (ffffffff814a1312)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
```
```
In drivers/pci/ats.c (ffffffff814a2863)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_queue_depth
```
```
In drivers/pci/iov.c (ffffffff814a37cc)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
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
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155c82b)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/char/agp/generic.c (ffffffff81570633)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
```
```
In drivers/char/agp/isoch.c (ffffffff81571827)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81572ae3)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8157323d)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81574466)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff8157608a)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
```
```
In drivers/iommu/amd_iommu.c (ffffffff815851ba)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158b116)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
```
```
In drivers/ata/libata-core.c (ffffffff816216a5)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:pci_test_config_bits
```
```
In drivers/ata/ata_piix.c (ffffffff8163d09a)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
```
```
In drivers/ata/pata_sis.c (ffffffff8163e546)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
```
```
In drivers/ata/ata_generic.c (ffffffff8163e791)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81641126)
Location: include/linux/pci.h:921
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816910b6)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8169d940)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/hwmon/hwmon.c (ffffffff81fdf81f)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/i386.c (ffffffff8175ae1c)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
```
In arch/x86/pci/fixup.c (ffffffff8175d50a)
Location: include/linux/pci.h:921
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/access.c (ffffffff8149ae9b)
Location: include/linux/pci.h:951
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8149e2f6)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff814a5f35)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
```
```
In drivers/pci/setup-res.c (ffffffff814ab066)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_update_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814ad067)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
```
In drivers/pci/vc.c (ffffffff814ae9b1)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (ffffffff814b4998)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814b9a6c)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_remove
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814be3d0)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/msi.c (ffffffff814c2ef0)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
```
```
In drivers/pci/ats.c (ffffffff814c44b3)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_queue_depth
```
```
In drivers/pci/iov.c (ffffffff814c542c)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158916b)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/char/agp/generic.c (ffffffff8159ccf3)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
```
```
In drivers/char/agp/isoch.c (ffffffff8159dee7)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8159f155)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8159f8ad)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a0ae6)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff815a271a)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b22d8)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b8866)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
```
```
In drivers/ata/libata-core.c (ffffffff81652225)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:pci_test_config_bits
```
```
In drivers/ata/ata_piix.c (ffffffff8166e11a)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
```
```
In drivers/ata/pata_sis.c (ffffffff8166f5b6)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
```
```
In drivers/ata/ata_generic.c (ffffffff8166f813)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81672212)
Location: include/linux/pci.h:951
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bf166)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
```
```
In drivers/usb/host/ehci-pci.c (ffffffff816cba74)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/hwmon/hwmon.c (ffffffff8201d48a)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/i386.c (ffffffff8178737c)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
```
In arch/x86/pci/fixup.c (ffffffff81789a3a)
Location: include/linux/pci.h:951
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4830)
Location: drivers/pci/access.c:913
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:hibmc_fixup_vgaarb
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pcie-dpc.c:dpc_remove
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff814a4830-ffffffff814a48a2: pci_read_config_word.part.10 (STB_LOCAL)
ffffffff814a48b0-ffffffff814a48d9: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3600)
Location: drivers/pci/access.c:913
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pcie-dpc.c:dpc_remove
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff814e3600-ffffffff814e3677: pci_read_config_word.part.10 (STB_LOCAL)
ffffffff814e3680-ffffffff814e36a9: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81512e80)
Location: drivers/pci/access.c:546
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81512e80-ffffffff81512f13: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528680)
Location: drivers/pci/access.c:546
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81528680-ffffffff815286b3: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557910)
Location: drivers/pci/access.c:546
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81557910-ffffffff81557947: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578f40)
Location: drivers/pci/access.c:537
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81578f40-ffffffff81578f77: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e3c6)
Location: drivers/pci/access.c:533
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_word
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_msi_setup_pci_dev
  - drivers/pci/probe.c:pci_msi_setup_pci_dev
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_disable_acs_redir
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_mappable_entries
  - drivers/char/agp/intel-gtt.c:i965_gtt_total_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_has_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_has_feat
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8161df50-ffffffff8161df87: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644bf4)
Location: drivers/pci/access.c:533
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_word
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_disable_acs_redir
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi.c:pci_msix_init
  - drivers/pci/msi.c:pci_msi_init
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_mappable_entries
  - drivers/char/agp/intel-gtt.c:i965_gtt_total_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_has_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_has_feat
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81644770-ffffffff816447a7: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627883)
Location: drivers/pci/access.c:533
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_word
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi.c:pci_msix_init
  - drivers/pci/msi.c:pci_msi_init
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff816274f0-ffffffff81627527: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81697183)
Location: drivers/pci/access.c:533
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_word
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi.c:pci_msix_init
  - drivers/pci/msi.c:pci_msi_init
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_suspend
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_get_irq_count
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_get_irq_count
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81696d40-ffffffff81696d77: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b8926)
Location: drivers/pci/access.c:538
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_word
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_set_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:__pci_pme_active
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:msix_setup_msi_descs
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:quirk_disable_pxb
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_memory_lock_and_enable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_get_irq_count
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_get_irq_count
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff817b7d40-ffffffff817b7d8d: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d3386)
Location: drivers/pci/access.c:544
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_word
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_set_mwi
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:__pci_pme_active
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/msi/api.c:pci_msix_vec_count
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_completed
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:dpc_log_size
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:quirk_disable_pxb
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff818d25d0-ffffffff818d261d: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff819163ea)
Location: drivers/pci/access.c:558
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_word
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_set_mwi
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:__pci_pme_active
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/msi/api.c:pci_msix_vec_count
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_completed
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:dpc_log_size
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:quirk_disable_pxb
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff819155d0-ffffffff8191561d: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195e41a)
Location: drivers/pci/access.c:556
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_word
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_mmio
  - drivers/pci/probe.c:pci_read_bridge_mmio
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_disable_parity
  - drivers/pci/pci.c:pci_set_mwi
  - drivers/pci/pci.c:pci_clear_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:__pci_pme_active
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:__pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_status_get_and_clear_errors
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/msi/api.c:pci_msix_vec_count
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_restore_msix_state
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_completed
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:dpc_log_size
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:quirk_intel_mc_errata
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:asus_hides_smbus_lpc
  - drivers/pci/quirks.c:quirk_disable_pxb
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/ats.c:pci_disable_ats
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/virtio/virtio_pci_common.c:virtio_pci_resume
  - drivers/virtio/virtio_pci_common.c:virtio_pci_suspend
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gmch_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:amd_rp_pme_resume
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8195d540-ffffffff8195d58d: pci_read_config_word (STB_GLOBAL)
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
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106dbf80)
Location: drivers/pci/access.c:537
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffff8000106dbf80-ffff8000106dbff0: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877228)
Location: drivers/pci/access.c:537
Inline: True
Direct callers:
  - arch/arm/kernel/bios32.c:pcibios_fixup_bus
  - arch/arm/kernel/bios32.c:pcibios_fixup_bus
  - arch/arm/kernel/bios32.c:pcibios_fixup_bus
  - arch/arm/kernel/bios32.c:pcibios_fixup_bus
  - arch/arm/kernel/bios32.c:pcibios_bus_report_status
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
c0877228-c0877270: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852880)
Location: drivers/pci/access.c:537
Inline: True
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_dev_break_write
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_fixup_actag
  - arch/powerpc/platforms/powernv/ocxl.c:find_dvsec_from_pos
  - arch/powerpc/platforms/powernv/ocxl.c:find_dvsec_from_pos
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_irq_count
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
c000000000852880-c0000000008528d0: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3b62)
Location: drivers/pci/access.c:537
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffe0004b3b62-ffffffe0004b3bc0: pci_read_config_word (STB_GLOBAL)
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
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d460)
Location: drivers/pci/access.c:537
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/nvme/host/pci.c:nvme_timeout
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8156d460-ffffffff8156d497: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155bbd0)
Location: drivers/pci/access.c:537
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/nvme/host/pci.c:nvme_timeout
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8155bbd0-ffffffff8155bc07: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156cc90)
Location: drivers/pci/access.c:537
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8156cc90-ffffffff8156ccc7: pci_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_word(const struct pci_dev *dev, int where, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587190)
Location: drivers/pci/access.c:537
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pci_set_vga_state
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pme_restore
  - drivers/pci/pci.c:pci_check_pme_status
  - drivers/pci/pci.c:do_pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/dpc.c:dpc_remove
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_msix_vec_count
  - drivers/pci/msi.c:pci_msi_vec_count
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_page_aligned
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
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
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/video/fbdev/efifb.c:efifb_fixup_resources
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81587190-ffffffff815871c7: pci_read_config_word (STB_GLOBAL)
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
