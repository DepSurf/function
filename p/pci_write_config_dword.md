# Function: <code>pci_write_config_dword</code>

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
In arch/x86/events/amd/ibs.c (ffffffff81009822)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101af4d)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/quirks.c (ffffffff810351d0)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ec04)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810630ff)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106691c)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107a258)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
```
```
In drivers/pci/access.c (ffffffff8142e3ca)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
```
In drivers/pci/probe.c (ffffffff8142fe9a)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
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
```
```
In drivers/pci/pci.c (ffffffff81434283)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_restore_config_dword
```
```
In drivers/pci/rom.c (ffffffff8143ceaa)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/rom.c:pci_disable_rom
```
```
In drivers/pci/setup-res.c (ffffffff8143d564)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
```
```
In drivers/pci/setup-bus.c (ffffffff8143df72)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
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
```
```
In drivers/pci/vc.c (ffffffff81440c71)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_save_restore_dwords
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (ffffffff81443fc6)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:vtd_mask_spec_errors
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81449d99)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff8144ad13)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
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
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814530fe)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
```
```
In drivers/pci/msi.c (ffffffff814546a8)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
```
```
In drivers/pci/htirq.c (ffffffff81455690)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
```
```
In drivers/pci/ats.c (ffffffff81455d17)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_pri
```
```
In drivers/pci/iov.c (ffffffff81456cf2)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_restore_iov_state
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814771d2)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150b66c)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/char/agp/generic.c (ffffffff8151d32c)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp_generic_enable
```
```
In drivers/char/agp/isoch.c (ffffffff8151e773)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8151f3a7)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
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
```
```
In drivers/char/agp/intel-agp.c (ffffffff815200dd)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
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
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81521aec)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
```
In drivers/char/agp/via-agp.c (ffffffff81522f26)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/char/agp/via-agp.c:via_configure
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815325d6)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
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
```
```
In drivers/ata/ata_piix.c (ffffffff815e2a16)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/ata/pata_sis.c (ffffffff815e4123)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816300e7)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
```
```
In arch/x86/pci/i386.c (ffffffff816f62e2)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
```
In arch/x86/pci/fixup.c (ffffffff816f8687)
Location: include/linux/pci.h:927
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
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
In arch/x86/events/amd/ibs.c (ffffffff81009c12)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a5cd)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/quirks.c (ffffffff810344fa)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ea44)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810631e7)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066b8a)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107bb08)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
```
```
In drivers/pci/access.c (ffffffff8147999a)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
```
In drivers/pci/probe.c (ffffffff8147b5fa)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff8147fc3f)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_restore_config_dword
```
```
In drivers/pci/rom.c (ffffffff81488de4)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_enable_rom
```
```
In drivers/pci/setup-res.c (ffffffff814894d0)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8148c001)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
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
```
```
In drivers/pci/vc.c (ffffffff8148cd50)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_save_restore_dwords
```
```
In drivers/pci/quirks.c (ffffffff81491389)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81496e41)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814971f1)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
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
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149f999)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
```
```
In drivers/pci/msi.c (ffffffff814a185d)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
```
```
In drivers/pci/htirq.c (ffffffff814a22c3)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
```
```
In drivers/pci/ats.c (ffffffff814a293e)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_pri
```
```
In drivers/pci/iov.c (ffffffff814a3eee)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814c570c)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155cd6f)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/char/agp/generic.c (ffffffff81570197)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_device_command
```
```
In drivers/char/agp/isoch.c (ffffffff81571a0b)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81572dfe)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
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
```
```
In drivers/char/agp/intel-agp.c (ffffffff81573207)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
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
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8157496d)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
```
In drivers/char/agp/via-agp.c (ffffffff81575f06)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/char/agp/via-agp.c:via_configure
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81fd6c55)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
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
```
```
In drivers/ata/ata_piix.c (ffffffff8163c736)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/ata/pata_sis.c (ffffffff8163e52c)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81691006)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In arch/x86/pci/i386.c (ffffffff8175af91)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
```
In arch/x86/pci/fixup.c (ffffffff8175d31a)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
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
In arch/x86/events/amd/ibs.c (ffffffff81009c52)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ab95)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/quirks.c (ffffffff8103413a)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e3cc)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810666da)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a7fd)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810800a8)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
```
```
In drivers/pci/access.c (ffffffff8149ae2a)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
```
```
In drivers/pci/probe.c (ffffffff8149ca7a)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff814a128f)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_restore_config_dword
```
```
In drivers/pci/rom.c (ffffffff814aa5b4)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_enable_rom
```
```
In drivers/pci/setup-res.c (ffffffff814aacc0)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814ad7f1)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
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
```
```
In drivers/pci/vc.c (ffffffff814ae540)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_save_restore_dwords
```
```
In drivers/pci/quirks.c (ffffffff814b2bf9)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b86ff)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814b8b47)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
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
```
```
In drivers/pci/pcie/ptm.c (ffffffff814ba024)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c1519)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
```
```
In drivers/pci/msi.c (ffffffff814c34ad)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
```
```
In drivers/pci/htirq.c (ffffffff814c3f13)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
```
```
In drivers/pci/ats.c (ffffffff814c458e)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_pri
```
```
In drivers/pci/iov.c (ffffffff814c5c7e)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814e76fc)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff815896af)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/char/agp/generic.c (ffffffff8159c857)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_device_command
```
```
In drivers/char/agp/isoch.c (ffffffff8159e0cb)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8159f46c)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
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
```
```
In drivers/char/agp/intel-agp.c (ffffffff8159f877)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
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
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a0fed)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
```
In drivers/char/agp/via-agp.c (ffffffff815a2596)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/char/agp/via-agp.c:via_configure
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815b4bd7)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
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
```
```
In drivers/ata/ata_piix.c (ffffffff8166d7b6)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/ata/pata_sis.c (ffffffff8166f59c)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bf0b6)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In arch/x86/pci/i386.c (ffffffff817874e5)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
```
In arch/x86/pci/fixup.c (ffffffff8178984a)
Location: include/linux/pci.h:968
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4bb7)
Location: drivers/pci/access.c:950
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
  - drivers/pci/quirks.c:quirk_fix_vulcan_ahci_bars
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
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
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff814a4a00-ffffffff814a4a32: pci_write_config_dword.part.13 (STB_LOCAL)
ffffffff814a4a40-ffffffff814a4a62: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3997)
Location: drivers/pci/access.c:950
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
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
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
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
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
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff814e37d0-ffffffff814e3808: pci_write_config_dword.part.13 (STB_LOCAL)
ffffffff814e3810-ffffffff814e3832: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815133ba)
Location: drivers/pci/access.c:583
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aer.c:aer_error_resume
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81513050-ffffffff8151309c: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528af3)
Location: drivers/pci/access.c:583
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81528760-ffffffff8152878a: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815579f0)
Location: drivers/pci/access.c:583
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:program_hpx_type3
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff815579f0-ffffffff81557a1e: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81579020)
Location: drivers/pci/access.c:574
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81579020-ffffffff8157904e: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e622)
Location: drivers/pci/access.c:570
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:setup_ibs_ctl
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_hpet_resume
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
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
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_nonisochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
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
  - drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_erratum_746_workaround
  - drivers/iommu/amd/init.c:amd_iommu_erratum_746_workaround
  - drivers/iommu/amd/init.c:amd_iommu_erratum_746_workaround
  - drivers/iommu/amd/init.c:amd_iommu_erratum_746_workaround
  - drivers/iommu/amd/init.c:iommu_read_l2
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8161e030-ffffffff8161e05e: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644e51)
Location: drivers/pci/access.c:570
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:setup_ibs_ctl
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_hpet_resume
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
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
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_nonisochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
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
  - drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_erratum_746_workaround
  - drivers/iommu/amd/init.c:amd_iommu_erratum_746_workaround
  - drivers/iommu/amd/init.c:amd_iommu_erratum_746_workaround
  - drivers/iommu/amd/init.c:amd_iommu_erratum_746_workaround
  - drivers/iommu/amd/init.c:iommu_read_l2
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81644850-ffffffff8164487e: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627af1)
Location: drivers/pci/access.c:570
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
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
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_read_l2
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff816275d0-ffffffff816275fe: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816973f1)
Location: drivers/pci/access.c:570
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
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
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:pci_msi_update_mask
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_read_l2
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81696e20-ffffffff81696e4e: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b7e80)
Location: drivers/pci/access.c:575
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/rom.c:pci_disable_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
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
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:pci_msi_update_mask
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_restore_aspm_l1ss_state
  - drivers/pci/pcie/aspm.c:pci_restore_aspm_l1ss_state
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/quirks.c:quirk_disable_amd_813x_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_read_l2
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff817b7e80-ffffffff817b7ec4: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d2750)
Location: drivers/pci/access.c:581
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/rom.c:pci_disable_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
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
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_suspend_ptm
  - drivers/pci/pcie/ptm.c:__pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/quirks.c:quirk_disable_amd_813x_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_abort
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff818d2750-ffffffff818d2794: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81915750)
Location: drivers/pci/access.c:595
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/rom.c:pci_disable_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
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
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_suspend_ptm
  - drivers/pci/pcie/ptm.c:__pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/quirks.c:quirk_disable_amd_813x_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_abort
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:chromeos_fixup_apl_pci_l1ss_capability
  - arch/x86/pci/fixup.c:chromeos_fixup_apl_pci_l1ss_capability
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81915750-ffffffff81915794: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195e10b)
Location: drivers/pci/access.c:593
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_clear_and_set_config_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_write_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/rom.c:pci_disable_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
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
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_suspend
  - drivers/pci/pcie/aer.c:aer_suspend
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_suspend_ptm
  - drivers/pci/pcie/ptm.c:__pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/quirks.c:quirk_disable_amd_813x_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_abort
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/ata/ata_piix.c:piix_remove_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_disable_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/fixup.c:chromeos_fixup_apl_pci_l1ss_capability
  - arch/x86/pci/fixup.c:chromeos_fixup_apl_pci_l1ss_capability
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8195d6c0-ffffffff8195d704: pci_write_config_dword (STB_GLOBAL)
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
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106dbb74)
Location: drivers/pci/access.c:574
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
**Symbols:**

```
ffff8000106dbab8-ffff8000106dbb20: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877ebc)
Location: drivers/pci/access.c:574
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
Direct callers:
  - arch/arm/kernel/bios32.c:pci_fixup_cy82c693
  - arch/arm/kernel/bios32.c:pci_fixup_cy82c693
  - arch/arm/kernel/bios32.c:pci_fixup_dec21142
  - arch/arm/kernel/bios32.c:pci_fixup_83c553
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
**Symbols:**

```
c0877338-c0877378: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0000000008529c0)
Location: drivers/pci/access.c:574
Inline: True
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:sriov_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
**Symbols:**

```
c0000000008529c0-c000000000852a08: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3ff2)
Location: drivers/pci/access.c:574
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
**Symbols:**

```
ffffffe0004b3cb2-ffffffe0004b3cfc: pci_write_config_dword (STB_GLOBAL)
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
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d540)
Location: drivers/pci/access.c:574
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8156d540-ffffffff8156d56e: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155bcb0)
Location: drivers/pci/access.c:574
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/iov.c:pci_iov_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8155bcb0-ffffffff8155bcde: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156cd70)
Location: drivers/pci/access.c:574
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8156cd70-ffffffff8156cd9e: pci_write_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_write_config_dword(const struct pci_dev *dev, int where, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587270)
Location: drivers/pci/access.c:574
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
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
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
  - drivers/pci/setup-res.c:pci_disable_bridge_window
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_cardbus_legacy
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msi_desc_mask_irq
  - drivers/pci/ats.c:pci_restore_pri_state
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
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81587270-ffffffff8158729e: pci_write_config_dword (STB_GLOBAL)
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
