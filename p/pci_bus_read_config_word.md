# Function: <code>pci_bus_read_config_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142db00)
Location: drivers/pci/access.c:57
Inline: False
Direct callers:
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
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
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
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
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
  - drivers/pci/ats.c:pci_ats_queue_depth
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_pri
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
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/char/agp/generic.c:agp3_generic_fetch_size
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_fetch_size
  - drivers/char/agp/intel-agp.c:intel_cleanup
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_fetch_size_agp3
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_133_cable_detect
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8142db00-ffffffff8142dba5: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81478e90)
Location: drivers/pci/access.c:57
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
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
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
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/pcie-dpc.c:dpc_remove
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
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
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
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
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81478e90-ffffffff81478f37: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149a2a0)
Location: drivers/pci/access.c:57
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
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
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
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/pcie/pcie-dpc.c:dpc_remove
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
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
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
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
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8149a2a0-ffffffff8149a347: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a3eb0)
Location: drivers/pci/access.c:65
Inline: True
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff814a3eb0-ffffffff814a3f17: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e2c20)
Location: drivers/pci/access.c:65
Inline: True
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff814e2c20-ffffffff814e2c8d: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81512ec1)
Location: drivers/pci/access.c:64
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_read_config_word
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81512a80-ffffffff81512aeb: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815282e0)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff815282e0-ffffffff8152834b: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557570)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81557570-ffffffff815575db: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578ba0)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81578ba0-ffffffff81578c0b: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161dbb0)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/pci.c:pci_find_ht_capability
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:pci_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8161dbb0-ffffffff8161dc1a: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816443d0)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/pci.c:pci_find_ht_capability
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:pci_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff816443d0-ffffffff8164443a: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627130)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/pci.c:pci_find_ht_capability
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:pci_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81627130-ffffffff8162719a: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81696a00)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/pci.c:pci_find_ht_capability
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:pci_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81696a00-ffffffff81696a6a: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b7950)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/pci.c:pci_find_ht_capability
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:pci_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff817b7950-ffffffff817b79d7: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d2140)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/pci.c:pci_find_ht_capability
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:pci_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff818d2140-ffffffff818d21c7: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81915140)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/pci.c:pci_find_ht_capability
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:pci_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81915140-ffffffff819151c7: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195d0b0)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/pci.c:pci_find_ht_capability
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:pci_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8195d0b0-ffffffff8195d137: pci_bus_read_config_word (STB_GLOBAL)
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
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106dbe58)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffff8000106dbe58-ffff8000106dbf80: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0876cf4)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
c0876cf4-c0876dc0: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852120)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:early_read_config_word
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
c000000000852120-c00000000085224c: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3620)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffe0004b3620-ffffffe0004b36aa: pci_bus_read_config_word (STB_GLOBAL)
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
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d0c0)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8156d0c0-ffffffff8156d12b: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155b830)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8155b830-ffffffff8155b89b: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156c8f0)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8156c8f0-ffffffff8156c95b: pci_bus_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_bus_read_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81586df0)
Location: drivers/pci/access.c:64
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81586df0-ffffffff81586e5b: pci_bus_read_config_word (STB_GLOBAL)
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
