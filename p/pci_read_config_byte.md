# Function: <code>pci_read_config_byte</code>

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
In arch/x86/kernel/quirks.c (ffffffff810354ed)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In drivers/pci/probe.c (ffffffff8142f966)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
```
```
In drivers/pci/pci.c (ffffffff81433b34)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
```
```
In drivers/pci/quirks.c (ffffffff81442d26)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814500bb)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/iov.c (ffffffff81456eab)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/acpi_processor.c (ffffffff81482295)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff814c148b)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150a2b8)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/char/agp/isoch.c (ffffffff8151e9d8)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/intel-agp.c (ffffffff81520a36)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_815_configure
```
```
In drivers/char/agp/via-agp.c (ffffffff8152308a)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_fetch_size
```
```
In drivers/ata/libata-core.c (ffffffff815c907d)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:pci_test_config_bits
```
```
In drivers/ata/libata-sff.c (ffffffff815dd192)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/ata/ata_piix.c (ffffffff815e2cbd)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/ata/pata_sis.c (ffffffff815e3a66)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8163cbec)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816622e0)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
```
In drivers/hwmon/hwmon.c (ffffffff81fb2c3d)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/xen.c (ffffffff816f74f6)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
```
```
In arch/x86/pci/fixup.c (ffffffff816f82d7)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
```
```
In arch/x86/pci/irq.c (ffffffff816f911c)
Location: include/linux/pci.h:906
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:read_config_nybble
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
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
In arch/x86/kernel/quirks.c (ffffffff810346ed)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In drivers/pci/probe.c (ffffffff8147c9ce)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
```
```
In drivers/pci/pci.c (ffffffff8148042b)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
```
```
In drivers/pci/quirks.c (ffffffff81492fd3)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8149c88b)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/iov.c (ffffffff814a3ad3)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/acpi_processor.c (ffffffff814d0d9e)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff815120e0)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155c698)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/char/agp/isoch.c (ffffffff81571845)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/intel-agp.c (ffffffff81573a0a)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
```
```
In drivers/char/agp/via-agp.c (ffffffff81575fca)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_fetch_size
```
```
In drivers/ata/libata-core.c (ffffffff8162165d)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:pci_test_config_bits
```
```
In drivers/ata/libata-sff.c (ffffffff81636f1a)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/ata/ata_piix.c (ffffffff8163d1c9)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
```
```
In drivers/ata/pata_sis.c (ffffffff8163e597)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8169d9f1)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c250d)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
```
In drivers/hwmon/hwmon.c (ffffffff81fdf80a)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/xen.c (ffffffff8175c196)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
```
```
In arch/x86/pci/fixup.c (ffffffff8175d256)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
```
```
In arch/x86/pci/irq.c (ffffffff8175ed16)
Location: include/linux/pci.h:917
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
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
In arch/x86/kernel/quirks.c (ffffffff8103432d)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In drivers/pci/probe.c (ffffffff8149df2e)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
```
```
In drivers/pci/pci.c (ffffffff814a1a7b)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
```
```
In drivers/pci/quirks.c (ffffffff814b4963)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814be40b)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/iov.c (ffffffff814c5742)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/acpi_processor.c (ffffffff814f2e54)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8153e470)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81588fd8)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/char/agp/isoch.c (ffffffff8159df05)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/agp/intel-agp.c (ffffffff815a007a)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
```
```
In drivers/char/agp/via-agp.c (ffffffff815a265a)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_fetch_size
```
```
In drivers/ata/libata-core.c (ffffffff816521dd)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:pci_test_config_bits
```
```
In drivers/ata/libata-sff.c (ffffffff81667fba)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/ata/ata_piix.c (ffffffff8166e249)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
```
```
In drivers/ata/pata_sis.c (ffffffff8166f607)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
```
```
In drivers/usb/host/ehci-pci.c (ffffffff816cbafe)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f04cd)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
```
In drivers/hwmon/hwmon.c (ffffffff8201d475)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/xen.c (ffffffff81788706)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
```
```
In arch/x86/pci/fixup.c (ffffffff81789786)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
```
```
In arch/x86/pci/irq.c (ffffffff8178b246)
Location: include/linux/pci.h:947
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a42d0)
Location: drivers/pci/access.c:903
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/iov.c:pci_iov_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
```
**Symbols:**

```
ffffffff814a42d0-ffffffff814a434c: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3050)
Location: drivers/pci/access.c:903
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/iov.c:pci_iov_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
```
**Symbols:**

```
ffffffff814e3050-ffffffff814e30d2: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81512df0)
Location: drivers/pci/access.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
```
**Symbols:**

```
ffffffff81512df0-ffffffff81512e72: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528650)
Location: drivers/pci/access.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
```
**Symbols:**

```
ffffffff81528650-ffffffff8152867e: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815578d0)
Location: drivers/pci/access.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
```
**Symbols:**

```
ffffffff815578d0-ffffffff81557902: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578f00)
Location: drivers/pci/access.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
```
**Symbols:**

```
ffffffff81578f00-ffffffff81578f32: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161df10)
Location: drivers/pci/access.c:523
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:check_via_agp3
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_sata_map
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_irq_count
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_amd756_get
  - arch/x86/pci/irq.c:pirq_vlsi_get
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_cyrix_get
  - arch/x86/pci/irq.c:pirq_opti_get
  - arch/x86/pci/irq.c:pirq_ite_get
  - arch/x86/pci/irq.c:pirq_via586_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:pirq_ali_get
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff8161df10-ffffffff8161df42: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644730)
Location: drivers/pci/access.c:523
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:check_via_agp3
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_sata_map
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_irq_count
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_amd756_get
  - arch/x86/pci/irq.c:pirq_vlsi_get
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_cyrix_get
  - arch/x86/pci/irq.c:pirq_opti_get
  - arch/x86/pci/irq.c:pirq_ite_get
  - arch/x86/pci/irq.c:pirq_via586_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:pirq_ali_get
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff81644730-ffffffff81644762: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816274b0)
Location: drivers/pci/access.c:523
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:check_via_agp3
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_sata_map
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_irq_count
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_amd756_get
  - arch/x86/pci/irq.c:pirq_vlsi_get
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_cyrix_get
  - arch/x86/pci/irq.c:pirq_opti_get
  - arch/x86/pci/irq.c:pirq_ite_get
  - arch/x86/pci/irq.c:pirq_via586_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:pirq_ali_get
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff816274b0-ffffffff816274e2: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81696d00)
Location: drivers/pci/access.c:523
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:check_via_agp3
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_sata_map
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_get_irq_count
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_amd756_get
  - arch/x86/pci/irq.c:pirq_vlsi_get
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_cyrix_get
  - arch/x86/pci/irq.c:pirq_opti_get
  - arch/x86/pci/irq.c:pirq_ite_get
  - arch/x86/pci/irq.c:pirq_via586_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_ib_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:pirq_ali_get
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff81696d00-ffffffff81696d32: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b7cf0)
Location: drivers/pci/access.c:528
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:check_via_agp3
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_sata_map
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_get_irq_count
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_amd756_get
  - arch/x86/pci/irq.c:pirq_vlsi_get
  - arch/x86/pci/irq.c:pirq_sis503_set
  - arch/x86/pci/irq.c:pirq_sis503_get
  - arch/x86/pci/irq.c:pirq_sis497_set
  - arch/x86/pci/irq.c:pirq_sis497_get
  - arch/x86/pci/irq.c:pirq_cyrix_get
  - arch/x86/pci/irq.c:pirq_opti_get
  - arch/x86/pci/irq.c:pirq_ite_get
  - arch/x86/pci/irq.c:pirq_via586_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_ib_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:pirq_ali_get
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff817b7cf0-ffffffff817b7d38: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d2570)
Location: drivers/pci/access.c:534
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_sata_map
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_amd756_get
  - arch/x86/pci/irq.c:pirq_sis503_set
  - arch/x86/pci/irq.c:pirq_sis503_get
  - arch/x86/pci/irq.c:pirq_sis497_set
  - arch/x86/pci/irq.c:pirq_sis497_get
  - arch/x86/pci/irq.c:pirq_cyrix_get
  - arch/x86/pci/irq.c:pirq_opti_get
  - arch/x86/pci/irq.c:pirq_ite_get
  - arch/x86/pci/irq.c:pirq_via586_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_ib_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:pirq_ali_get
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff818d2570-ffffffff818d25b8: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81915570)
Location: drivers/pci/access.c:548
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_sata_map
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_amd756_get
  - arch/x86/pci/irq.c:pirq_sis503_set
  - arch/x86/pci/irq.c:pirq_sis503_get
  - arch/x86/pci/irq.c:pirq_sis497_set
  - arch/x86/pci/irq.c:pirq_sis497_get
  - arch/x86/pci/irq.c:pirq_cyrix_get
  - arch/x86/pci/irq.c:pirq_opti_get
  - arch/x86/pci/irq.c:pirq_ite_get
  - arch/x86/pci/irq.c:pirq_via586_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_ib_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:pirq_ali_get
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff81915570-ffffffff819155b8: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195d4e0)
Location: drivers/pci/access.c:546
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_jmicron_ata
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:ich6_lpc_acpi_gpio
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_ich4_lpc_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_sata_map
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_amd756_get
  - arch/x86/pci/irq.c:pirq_sis503_set
  - arch/x86/pci/irq.c:pirq_sis503_get
  - arch/x86/pci/irq.c:pirq_sis497_set
  - arch/x86/pci/irq.c:pirq_sis497_get
  - arch/x86/pci/irq.c:pirq_cyrix_get
  - arch/x86/pci/irq.c:pirq_opti_get
  - arch/x86/pci/irq.c:pirq_ite_get
  - arch/x86/pci/irq.c:pirq_via586_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_via_get
  - arch/x86/pci/irq.c:pirq_ib_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:pirq_ali_get
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff8195d4e0-ffffffff8195d528: pci_read_config_byte (STB_GLOBAL)
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
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106db870)
Location: drivers/pci/access.c:527
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
```
**Symbols:**

```
ffff8000106db870-ffff8000106db8e0: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c08771e0)
Location: drivers/pci/access.c:527
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
```
**Symbols:**

```
c08771e0-c0877228: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852830)
Location: drivers/pci/access.c:527
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_device
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_device
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_fixup_actag
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_irq_count
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_fill_vconfig_bytes
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
```
**Symbols:**

```
c000000000852830-c000000000852880: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3b04)
Location: drivers/pci/access.c:527
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/of.c:of_irq_parse_and_map_pci
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
```
**Symbols:**

```
ffffffe0004b3b04-ffffffe0004b3b62: pci_read_config_byte (STB_GLOBAL)
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
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d420)
Location: drivers/pci/access.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
```
**Symbols:**

```
ffffffff8156d420-ffffffff8156d452: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155bb90)
Location: drivers/pci/access.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
```
**Symbols:**

```
ffffffff8155bb90-ffffffff8155bbc2: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156cc50)
Location: drivers/pci/access.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
```
**Symbols:**

```
ffffffff8156cc50-ffffffff8156cc82: pci_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_read_config_byte(const struct pci_dev *dev, int where, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587150)
Location: drivers/pci/access.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci-sysfs.c:subordinate_bus_number_show
  - drivers/pci/pci-sysfs.c:secondary_bus_number_show
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_nvidia_hda
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:quirk_intel_ntb
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_check_msi_mapping
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:msi_ht_cap_enabled
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_acpi
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/pci-quirks.c:usb_amd_pt_check_port
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_clear
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_sis_get
  - arch/x86/pci/irq.c:pirq_piix_get
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:read_config_nybble
```
**Symbols:**

```
ffffffff81587150-ffffffff81587182: pci_read_config_byte (STB_GLOBAL)
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
