# Function: <code>pci_bus_read_config_dword</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142dbb0)
Location: drivers/pci/access.c:58
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/rom.c:pci_disable_rom
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/vc.c:pci_vc_save_restore_dwords
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/htirq.c:__ht_create_irq
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/iommu/amd_iommu_init.c:iommu_read_l2
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8142dbb0-ffffffff8142dc54: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81478f40)
Location: drivers/pci/access.c:58
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_save_restore_dwords
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/htirq.c:__ht_create_irq
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_read_l2
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81478f40-ffffffff81478fe6: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149a350)
Location: drivers/pci/access.c:58
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_save_restore_dwords
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/htirq.c:__ht_create_irq
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_read_l2
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8149a350-ffffffff8149a3f6: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a3f20)
Location: drivers/pci/access.c:66
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff814a3f20-ffffffff814a3f86: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e2c90)
Location: drivers/pci/access.c:66
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff814e2c90-ffffffff814e2cfc: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81512f61)
Location: drivers/pci/access.c:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_read_config_dword
Direct callers:
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff81512af0-ffffffff81512b5a: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528350)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff81528350-ffffffff815283ba: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815575e0)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff815575e0-ffffffff8155764a: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578c10)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff81578c10-ffffffff81578c7a: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161dc20)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/iommu/intel/iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff8161dc20-ffffffff8161dc89: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644440)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff81644440-ffffffff816444a9: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816271a0)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff816271a0-ffffffff81627209: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81696a70)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff81696a70-ffffffff81696ad9: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b79e0)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff817b79e0-ffffffff817b7a64: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d21e0)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff818d21e0-ffffffff818d2264: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff819151e0)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff819151e0-ffffffff81915264: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195d150)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_clear_and_set_config_dword
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/iommu/intel/iommu.c:device_lookup_iommu
```
**Symbols:**

```
ffffffff8195d150-ffffffff8195d1d4: pci_bus_read_config_dword (STB_GLOBAL)
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
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106db208)
Location: drivers/pci/access.c:65
Inline: False
```
**Symbols:**

```
ffff8000106db208-ffff8000106db334: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0876dc0)
Location: drivers/pci/access.c:65
Inline: False
```
**Symbols:**

```
c0876dc0-c0876e8c: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852250)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:early_read_config_dword
```
**Symbols:**

```
c000000000852250-c00000000085237c: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b36aa)
Location: drivers/pci/access.c:65
Inline: False
```
**Symbols:**

```
ffffffe0004b36aa-ffffffe0004b3734: pci_bus_read_config_dword (STB_GLOBAL)
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
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d130)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff8156d130-ffffffff8156d19a: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155b8a0)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff8155b8a0-ffffffff8155b90a: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156c960)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff8156c960-ffffffff8156c9ca: pci_bus_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_bus_read_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81586e60)
Location: drivers/pci/access.c:65
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff81586e60-ffffffff81586eca: pci_bus_read_config_dword (STB_GLOBAL)
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
