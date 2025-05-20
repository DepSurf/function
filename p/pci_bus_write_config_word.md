# Function: <code>pci_bus_write_config_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff8142e160)
Location: drivers/pci/access.c:60
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
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
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:__pci_setup_bridge
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:quirk_xio2000a
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/msi.c:pci_enable_msi_range
  - drivers/pci/msi.c:pci_enable_msi_range
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/ats.c:pci_enable_ats
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_enable_pri
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
  - drivers/char/agp/generic.c:agp3_generic_configure
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
  - drivers/char/agp/intel-gtt.c:intel_enable_gtt
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_old_set_dmamode
  - drivers/ata/pata_sis.c:sis_66_set_dmamode
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/ata/ata_generic.c:ata_generic_init_one
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:sb800_prefetch
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/hwmon/hwmon.c:hwmon_init
```
**Symbols:**

```
ffffffff8142e160-ffffffff8142e1c7: pci_bus_write_config_word.part.6 (STB_LOCAL)
ffffffff8142e1d0-ffffffff8142e1ee: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff8147991a)
Location: drivers/pci/access.c:60
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
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_std_enable_acs
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
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
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
```
**Symbols:**

```
ffffffff81479730-ffffffff81479797: pci_bus_write_config_word.part.8 (STB_LOCAL)
ffffffff814797a0-ffffffff814797be: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/access.c (ffffffff8149adaa)
Location: drivers/pci/access.c:60
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
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_clear_mwi
  - drivers/pci/pci.c:__pci_set_master
  - drivers/pci/pci.c:pci_std_enable_acs
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
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
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
```
**Symbols:**

```
ffffffff8149abc0-ffffffff8149ac27: pci_bus_write_config_word.part.11 (STB_LOCAL)
ffffffff8149ac30-ffffffff8149ac4e: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a3fb0)
Location: drivers/pci/access.c:68
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff814a3fb0-ffffffff814a3fd9: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e2d30)
Location: drivers/pci/access.c:68
Inline: True
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff814e2d30-ffffffff814e2d5f: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8151331e)
Location: drivers/pci/access.c:67
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_word
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff81512b90-ffffffff81512bbf: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815283f0)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff815283f0-ffffffff8152841f: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557680)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff81557680-ffffffff815576af: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578cb0)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff81578cb0-ffffffff81578cdf: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161dcc0)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff8161dcc0-ffffffff8161dcef: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816444e0)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff816444e0-ffffffff8164450f: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627240)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff81627240-ffffffff8162726f: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81696b10)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff81696b10-ffffffff81696b3f: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b7ab0)
Location: drivers/pci/access.c:70
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff817b7ab0-ffffffff817b7afd: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d22d0)
Location: drivers/pci/access.c:70
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff818d22d0-ffffffff818d231d: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff819152d0)
Location: drivers/pci/access.c:70
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff819152d0-ffffffff8191531d: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195d240)
Location: drivers/pci/access.c:70
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff8195d240-ffffffff8195d28d: pci_bus_write_config_word (STB_GLOBAL)
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
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106dbc70)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffff8000106dbc70-ffff8000106dbd58: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0876f0c)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
c0876f0c-c0876f90: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852430)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:early_write_config_word
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
c000000000852430-c000000000852500: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b37a2)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffe0004b37a2-ffffffe0004b381e: pci_bus_write_config_word (STB_GLOBAL)
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
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d1d0)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff8156d1d0-ffffffff8156d1ff: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155b940)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff8155b940-ffffffff8155b96f: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156ca00)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff8156ca00-ffffffff8156ca2f: pci_bus_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_bus_write_config_word(struct pci_bus *bus, unsigned int devfn, int pos, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81586f00)
Location: drivers/pci/access.c:67
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
```
**Symbols:**

```
ffffffff81586f00-ffffffff81586f2f: pci_bus_write_config_word (STB_GLOBAL)
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
