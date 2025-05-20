# Function: <code>pci_read_config_dword</code>

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
In arch/x86/events/amd/ibs.c (ffffffff8100983a)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019106)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ad7f)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/quirks.c (ffffffff81034fcb)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ea86)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81063146)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066900)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/platform/atom/pmc_atom.c (ffffffff81f798d4)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107a369)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
```
```
In drivers/pci/access.c (ffffffff8142e56c)
Location: include/linux/pci.h:914
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8142fe79)
Location: include/linux/pci.h:914
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
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff8143424b)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/rom.c (ffffffff8143ce93)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/rom.c:pci_disable_rom
```
```
In drivers/pci/setup-res.c (ffffffff8143d57a)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8144010b)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
```
In drivers/pci/vc.c (ffffffff81440c4c)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
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
```
```
In drivers/pci/quirks.c (ffffffff81443446)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
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
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81448e41)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81449c21)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
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
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff8144acd9)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
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
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814530c2)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
```
```
In drivers/pci/msi.c (ffffffff81453b03)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
```
```
In drivers/pci/htirq.c (ffffffff81455558)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pci/htirq.c:__ht_create_irq
```
```
In drivers/pci/ats.c (ffffffff81455d02)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_pri
```
```
In drivers/pci/iov.c (ffffffff81456ccb)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pnp/resource.c (ffffffff814b8e74)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/pnp/quirks.c (ffffffff814bb2c2)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff814c14bf)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150a581)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/char/agp/generic.c (ffffffff8151cd87)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
```
```
In drivers/char/agp/isoch.c (ffffffff8151e417)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8151f224)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
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
```
```
In drivers/char/agp/intel-agp.c (ffffffff81520ff6)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_815_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815219e5)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff81522ee6)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816f4bc0)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_read_l2
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
```
```
In drivers/iommu/intel-iommu.c (ffffffff81fab8bb)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/ata/libata-core.c (ffffffff815c90a7)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:pci_test_config_bits
```
```
In drivers/ata/ata_piix.c (ffffffff815e3280)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/ata/pata_sis.c (ffffffff815e3f66)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_init_one
```
```
In drivers/ata/ata_generic.c (ffffffff815e4af5)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/ata/ata_generic.c:ata_generic_init_one
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8163010b)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81634ab8)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8163cc9b)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In arch/x86/pci/i386.c (ffffffff816f62c1)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
```
In arch/x86/pci/xen.c (ffffffff816f7950)
Location: include/linux/pci.h:914
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff816f8636)
Location: include/linux/pci.h:914
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
In arch/x86/events/amd/ibs.c (ffffffff81009c2a)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018436)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a28f)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/quirks.c (ffffffff810344a6)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ecf8)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81f9cbdc)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81f9da9b)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/platform/atom/pmc_atom.c (ffffffff81fa1fd8)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107bc17)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
```
```
In drivers/pci/access.c (ffffffff81479b2c)
Location: include/linux/pci.h:925
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8147b5d9)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
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
```
```
In drivers/pci/pci.c (ffffffff81480b47)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
```
```
In drivers/pci/rom.c (ffffffff81488dcd)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_enable_rom
```
```
In drivers/pci/setup-res.c (ffffffff814893b5)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8148bfa2)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
```
In drivers/pci/vc.c (ffffffff8148cf42)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
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
```
```
In drivers/pci/quirks.c (ffffffff81493046)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
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
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8149509d)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81495ee1)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
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
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814971b0)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
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
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149f952)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
```
```
In drivers/pci/msi.c (ffffffff814a0448)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
```
```
In drivers/pci/htirq.c (ffffffff814a2198)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pci/htirq.c:__ht_create_irq
```
```
In drivers/pci/ats.c (ffffffff814a2922)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_pri
```
```
In drivers/pci/iov.c (ffffffff814a3942)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pnp/resource.c (ffffffff815088d9)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/pnp/quirks.c (ffffffff8150ad3e)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81512538)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155c971)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/char/agp/generic.c (ffffffff81570163)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_collect_device_status
```
```
In drivers/char/agp/isoch.c (ffffffff81571695)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81572db0)
Location: include/linux/pci.h:925
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
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
```
In drivers/char/agp/intel-agp.c (ffffffff81573e57)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8157487a)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff81576443)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81fd699b)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_read_l2
```
```
In drivers/iommu/intel-iommu.c (ffffffff81fd8374)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/ata/libata-core.c (ffffffff81621687)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:pci_test_config_bits
```
```
In drivers/ata/ata_piix.c (ffffffff8163cf9a)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/ata/pata_sis.c (ffffffff8163e511)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
```
```
In drivers/ata/ata_generic.c (ffffffff8163e810)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/ata/ata_generic.c:ata_generic_init_one
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81690d6b)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81694f41)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8169d8a3)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8174749f)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In arch/x86/pci/i386.c (ffffffff8175ae11)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
```
In arch/x86/pci/xen.c (ffffffff8175c60d)
Location: include/linux/pci.h:925
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff8175d2c6)
Location: include/linux/pci.h:925
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
In arch/x86/events/amd/ibs.c (ffffffff81009c6a)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018606)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a79f)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/quirks.c (ffffffff81034646)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e676)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81fd812f)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81fd9035)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/platform/atom/pmc_atom.c (ffffffff81fdd619)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810801b7)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
```
```
In drivers/pci/access.c (ffffffff8149afbc)
Location: include/linux/pci.h:955
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8149ca59)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
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
```
```
In drivers/pci/pci.c (ffffffff814a2207)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
```
```
In drivers/pci/rom.c (ffffffff814aa59d)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_enable_rom
```
```
In drivers/pci/setup-res.c (ffffffff814aab80)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814ad792)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
```
In drivers/pci/vc.c (ffffffff814ae732)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
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
```
```
In drivers/pci/quirks.c (ffffffff814b49d6)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
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
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff814b6a4d)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b7878)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
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
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814b8b08)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
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
```
```
In drivers/pci/pcie/ptm.c (ffffffff814b9fe6)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c14d2)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
```
```
In drivers/pci/msi.c (ffffffff814c1fe5)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
```
```
In drivers/pci/htirq.c (ffffffff814c3de8)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pci/htirq.c:__ht_create_irq
```
```
In drivers/pci/ats.c (ffffffff814c4572)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_pri
```
```
In drivers/pci/iov.c (ffffffff814c55a2)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pnp/resource.c (ffffffff8152caf9)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/pnp/quirks.c (ffffffff8152ef5e)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8153e8df)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff815892b1)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
```
```
In drivers/char/agp/generic.c (ffffffff8159c823)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_collect_device_status
```
```
In drivers/char/agp/isoch.c (ffffffff8159dd55)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8159f429)
Location: include/linux/pci.h:955
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
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
```
```
In drivers/char/agp/intel-agp.c (ffffffff815a04c7)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a0efa)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff815a2ad3)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815b4bf0)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_read_l2
```
```
In drivers/iommu/intel-iommu.c (ffffffff82015f0d)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/ata/libata-core.c (ffffffff81652207)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:pci_test_config_bits
```
```
In drivers/ata/ata_piix.c (ffffffff8166e01a)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/ata/pata_sis.c (ffffffff8166f581)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
```
```
In drivers/ata/ata_generic.c (ffffffff8166f895)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/ata/ata_generic.c:ata_generic_init_one
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bee1b)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c34d1)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff816cb9c1)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8177acc4)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In arch/x86/pci/i386.c (ffffffff817874c1)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
```
In arch/x86/pci/xen.c (ffffffff81788b7d)
Location: include/linux/pci.h:955
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
```
In arch/x86/pci/fixup.c (ffffffff817897f6)
Location: include/linux/pci.h:955
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
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff814a48e0)
Location: drivers/pci/access.c:923
Inline: True
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
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
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
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_enable_msix
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
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
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
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff814a48e0-ffffffff814a4951: pci_read_config_dword.part.11 (STB_LOCAL)
ffffffff814a4960-ffffffff814a4987: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff814e36b0)
Location: drivers/pci/access.c:923
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
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
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
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
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
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
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
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
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
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
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff814e36b0-ffffffff814e3726: pci_read_config_dword.part.11 (STB_LOCAL)
ffffffff814e3730-ffffffff814e3757: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81512f20)
Location: drivers/pci/access.c:556
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
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
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_error_resume
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:get_device_error_info
  - drivers/pci/pcie/aer.c:get_device_error_info
  - drivers/pci/pcie/aer.c:get_device_error_info
  - drivers/pci/pcie/aer.c:get_device_error_info
  - drivers/pci/pcie/aer.c:get_device_error_info
  - drivers/pci/pcie/aer.c:get_device_error_info
  - drivers/pci/pcie/aer.c:get_device_error_info
  - drivers/pci/pcie/aer.c:get_device_error_info
  - drivers/pci/pcie/aer.c:get_device_error_info
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/dpc.c:dpc_irq
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
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
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81512f20-ffffffff81512fb0: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815286c0)
Location: drivers/pci/access.c:556
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
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
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
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
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
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
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff815286c0-ffffffff815286f1: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557950)
Location: drivers/pci/access.c:556
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
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
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:program_hpx_type3
  - drivers/pci/probe.c:program_hpx_type3
  - drivers/pci/probe.c:program_hpx_type3
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
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
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81557950-ffffffff81557985: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578f80)
Location: drivers/pci/access.c:547
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
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
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
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
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81578f80-ffffffff81578fb5: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e485)
Location: drivers/pci/access.c:543
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:setup_ibs_ctl
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_hpet_resume
  - arch/x86/kernel/quirks.c:old_ich_force_hpet_resume
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_show
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_show
  - arch/x86/kernel/cpu/cacheinfo.c:amd_calc_l3_indices
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_cache_gart
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_nonisochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_nonisochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
  - drivers/char/agp/intel-gtt.c:intel_gtt_mappable_entries
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_erratum_746_workaround
  - drivers/iommu/amd/init.c:iommu_read_l2
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_port_base
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8161df90-ffffffff8161dfc5: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644cb3)
Location: drivers/pci/access.c:543
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:setup_ibs_ctl
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_hpet_resume
  - arch/x86/kernel/quirks.c:old_ich_force_hpet_resume
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_show
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_show
  - arch/x86/kernel/cpu/cacheinfo.c:amd_calc_l3_indices
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_cache_gart
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_nonisochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_nonisochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:amd64_fetch_size
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-agp.c:intel_8xx_tlbflush
  - drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
  - drivers/char/agp/intel-gtt.c:intel_gtt_mappable_entries
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_tlbflush_agp3
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_tlbflush
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_erratum_746_workaround
  - drivers/iommu/amd/init.c:iommu_read_l2
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_port_base
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff816447b0-ffffffff816447e5: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627944)
Location: drivers/pci/access.c:543
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_show
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_show
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_read_l2
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_port_base
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81627530-ffffffff81627565: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81697244)
Location: drivers/pci/access.c:543
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_show
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_show
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:amd_df_indirect_read
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich7_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_read_l2
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_port_base
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81696d80-ffffffff81696db5: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b89f5)
Location: drivers/pci/access.c:548
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_show
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_show
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_find_vsec_capability
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_find_next_ext_capability
  - drivers/pci/pci.c:pci_find_next_ext_capability
  - drivers/pci/rom.c:pci_disable_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pci_save_aspm_l1ss_state
  - drivers/pci/pcie/aspm.c:pci_save_aspm_l1ss_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/quirks.c:quirk_disable_amd_813x_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_inteli960ni_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_read_l2
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_port_base
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
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
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff817b7d90-ffffffff817b7ddb: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d3465)
Location: drivers/pci/access.c:554
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_show
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_show
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_dev_wait
  - drivers/pci/pci.c:pci_dev_wait
  - drivers/pci/pci.c:pci_find_vsec_capability
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_find_next_ext_capability
  - drivers/pci/pci.c:pci_find_next_ext_capability
  - drivers/pci/rom.c:pci_disable_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
  - drivers/pci/pcie/aspm.c:aspm_calc_l1ss_info
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_suspend_ptm
  - drivers/pci/pcie/ptm.c:__pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/quirks.c:quirk_disable_amd_813x_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_abort
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_inteli960ni_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_port_base
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
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
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff818d2630-ffffffff818d267b: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff819164c9)
Location: drivers/pci/access.c:568
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_show
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_show
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_dev_wait
  - drivers/pci/pci.c:pci_find_vsec_capability
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_find_next_ext_capability
  - drivers/pci/pci.c:pci_find_next_ext_capability
  - drivers/pci/rom.c:pci_disable_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_suspend_ptm
  - drivers/pci/pcie/ptm.c:__pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/quirks.c:quirk_disable_amd_813x_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_abort
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_inteli960ni_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_port_base
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
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
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:chromeos_fixup_apl_pci_l1ss_capability
  - arch/x86/pci/fixup.c:chromeos_fixup_apl_pci_l1ss_capability
  - arch/x86/pci/fixup.c:chromeos_save_apl_pci_l1ss_capability
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff81915630-ffffffff8191567b: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195e0e1)
Location: drivers/pci/access.c:566
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_clear_and_set_config_dword
  - drivers/pci/access.c:pcie_capability_read_dword
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_irp_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_pci_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_read_counter
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_purley_xeon_ras_cap
  - arch/x86/kernel/quirks.c:quirk_intel_brickland_xeon_ras_cap
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:amd_disable_seq_and_redirect_scrub
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:force_hpet_resume
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
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
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_show
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_show
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_set_subcaches
  - arch/x86/kernel/amd_nb.c:amd_get_subcaches
  - arch/x86/kernel/amd_nb.c:__amd_smn_rw
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_windows
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_ea_read
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_dev_wait
  - drivers/pci/pci.c:pci_find_vsec_capability
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_find_next_ext_capability
  - drivers/pci/pci.c:pci_find_next_ext_capability
  - drivers/pci/rom.c:pci_disable_rom
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_setup_msi_desc
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/msi/msi.c:__pci_read_msi_msg
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
  - drivers/pci/pcie/aspm.c:aspm_l1ss_init
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_suspend_ptm
  - drivers/pci/pcie/ptm.c:__pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/quirks.c:quirk_disable_amd_813x_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_broadcom_boot_interrupt
  - drivers/pci/quirks.c:quirk_disable_intel_boot_interrupt
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_ich6_lpc
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/pci/doe.c:pci_doe_send_req
  - drivers/pci/doe.c:pci_doe_abort
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_inteli960ni_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_generic_enable
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
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
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_port_base
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
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
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:chromeos_fixup_apl_pci_l1ss_capability
  - arch/x86/pci/fixup.c:chromeos_fixup_apl_pci_l1ss_capability
  - arch/x86/pci/fixup.c:chromeos_save_apl_pci_l1ss_capability
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8195d5a0-ffffffff8195d5eb: pci_read_config_dword (STB_GLOBAL)
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
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106db338)
Location: drivers/pci/access.c:547
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffff8000106db338-ffff8000106db3a8: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877270)
Location: drivers/pci/access.c:547
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
c0877270-c08772b8: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0000000008528d0)
Location: drivers/pci/access.c:547
Inline: True
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_fixup_actag
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/char/agp/isoch.c:agp_3_5_isochronous_node_enable
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
c0000000008528d0-c000000000852920: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3bc0)
Location: drivers/pci/access.c:547
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
```
**Symbols:**

```
ffffffe0004b3bc0-ffffffe0004b3c1e: pci_read_config_dword (STB_GLOBAL)
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
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d4a0)
Location: drivers/pci/access.c:547
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
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
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
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
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8156d4a0-ffffffff8156d4d5: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155bc10)
Location: drivers/pci/access.c:547
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
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
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
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
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8155bc10-ffffffff8155bc45: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156ccd0)
Location: drivers/pci/access.c:547
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
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
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
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
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff8156ccd0-ffffffff8156cd05: pci_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_read_config_dword(const struct pci_dev *dev, int where, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815871d0)
Location: drivers/pci/access.c:547
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
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
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
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
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_pci_read_mdr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:early_dump_pci_device
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_cfg_space_size_ext
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
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
  - drivers/pci/pci.c:pci_rebar_set_size
  - drivers/pci/pci.c:pci_rebar_get_current_size
  - drivers/pci/pci.c:pci_rebar_get_possible_sizes
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/rom.c:pci_enable_rom
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
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:vtd_mask_spec_errors
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:quirk_amd_ordering
  - drivers/pci/quirks.c:ich7_lpc_generic_decode
  - drivers/pci/quirks.c:ich6_lpc_generic_decode
  - drivers/pci/quirks.c:quirk_piix4_acpi
  - drivers/pci/quirks.c:piix4_io_quirk
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pci_clear_and_set_dword
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
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
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/dpc.c:dpc_process_rp_pio_error
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/generic.c:agp3_generic_cleanup
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/generic.c:agp3_generic_tlbflush
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
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_mode_filter
  - drivers/ata/pata_sis.c:sis_133_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:get_pci_parity_status
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_fixup_nforce2
```
**Symbols:**

```
ffffffff815871d0-ffffffff81587205: pci_read_config_dword (STB_GLOBAL)
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
