# Function: <code>pci_bus_write_config_dword</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff8142e1f0)
Location: drivers/pci/access.c:61
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_disable_event
  - arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event
  - arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event
  - arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_box
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/rom.c:pci_disable_rom
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
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
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
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
  - drivers/char/agp/intel-agp.c:intel_tlbflush
  - drivers/char/agp/intel-agp.c:intel_tlbflush
  - drivers/char/agp/intel-agp.c:intel_7505_configure
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
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/iommu/amd_iommu_init.c:iommu_write_l2
  - drivers/iommu/amd_iommu_init.c:iommu_write_l2
  - drivers/iommu/amd_iommu_init.c:iommu_read_l2
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8142e1f0-ffffffff8142e256: pci_bus_write_config_dword.part.7 (STB_LOCAL)
ffffffff8142e260-ffffffff8142e27b: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff8147999a)
Location: drivers/pci/access.c:61
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event
  - arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event
  - arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_disable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_save_restore_dwords
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_tlbflush
  - drivers/char/agp/intel-agp.c:intel_tlbflush
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_write_l2
  - drivers/iommu/amd_iommu_init.c:iommu_write_l2
  - drivers/iommu/amd_iommu_init.c:iommu_read_l2
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff814797c0-ffffffff81479826: pci_bus_write_config_dword.part.9 (STB_LOCAL)
ffffffff81479830-ffffffff8147984b: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff8149ae2a)
Location: drivers/pci/access.c:61
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event
  - arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_event
  - arch/x86/events/intel/uncore_snbep.c:knl_uncore_imc_enable_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_disable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_save_restore_dwords
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status
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
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_tlbflush
  - drivers/char/agp/intel-agp.c:intel_tlbflush
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_write_l2
  - drivers/iommu/amd_iommu_init.c:iommu_write_l2
  - drivers/iommu/amd_iommu_init.c:iommu_read_l2
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8149ac50-ffffffff8149acb6: pci_bus_write_config_dword.part.12 (STB_LOCAL)
ffffffff8149acc0-ffffffff8149acdb: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a3fe0)
Location: drivers/pci/access.c:69
Inline: True
```
**Symbols:**

```
ffffffff814a3fe0-ffffffff814a4008: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e2d60)
Location: drivers/pci/access.c:69
Inline: True
```
**Symbols:**

```
ffffffff814e2d60-ffffffff814e2d8e: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815133be)
Location: drivers/pci/access.c:68
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
**Symbols:**

```
ffffffff81512bc0-ffffffff81512bee: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528420)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
**Symbols:**

```
ffffffff81528420-ffffffff8152844e: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815576b0)
Location: drivers/pci/access.c:68
Inline: False
```
**Symbols:**

```
ffffffff815576b0-ffffffff815576de: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578ce0)
Location: drivers/pci/access.c:68
Inline: False
```
**Symbols:**

```
ffffffff81578ce0-ffffffff81578d0e: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161dcf0)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
**Symbols:**

```
ffffffff8161dcf0-ffffffff8161dd1e: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644510)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
**Symbols:**

```
ffffffff81644510-ffffffff8164453e: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627270)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
**Symbols:**

```
ffffffff81627270-ffffffff8162729e: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81696b40)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
**Symbols:**

```
ffffffff81696b40-ffffffff81696b6e: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b7b00)
Location: drivers/pci/access.c:71
Inline: False
```
**Symbols:**

```
ffffffff817b7b00-ffffffff817b7b4c: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d2330)
Location: drivers/pci/access.c:71
Inline: False
Direct callers:
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff818d2330-ffffffff818d237c: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81915330)
Location: drivers/pci/access.c:71
Inline: False
Direct callers:
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff81915330-ffffffff8191537c: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195d2a0)
Location: drivers/pci/access.c:71
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_clear_and_set_config_dword
```
**Symbols:**

```
ffffffff8195d2a0-ffffffff8195d2ec: pci_bus_write_config_dword (STB_GLOBAL)
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
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106db9c8)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
**Symbols:**

```
ffff8000106db9c8-ffff8000106dbab4: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0876f90)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
**Symbols:**

```
c0876f90-c0877014: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852500)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:early_write_config_dword
```
**Symbols:**

```
c000000000852500-c0000000008525d0: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b381e)
Location: drivers/pci/access.c:68
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
**Symbols:**

```
ffffffe0004b381e-ffffffe0004b389a: pci_bus_write_config_dword (STB_GLOBAL)
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
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d200)
Location: drivers/pci/access.c:68
Inline: False
```
**Symbols:**

```
ffffffff8156d200-ffffffff8156d22e: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155b970)
Location: drivers/pci/access.c:68
Inline: False
```
**Symbols:**

```
ffffffff8155b970-ffffffff8155b99e: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156ca30)
Location: drivers/pci/access.c:68
Inline: False
```
**Symbols:**

```
ffffffff8156ca30-ffffffff8156ca5e: pci_bus_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_bus_write_config_dword(struct pci_bus *bus, unsigned int devfn, int pos, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81586f30)
Location: drivers/pci/access.c:68
Inline: False
```
**Symbols:**

```
ffffffff81586f30-ffffffff81586f5e: pci_bus_write_config_dword (STB_GLOBAL)
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
