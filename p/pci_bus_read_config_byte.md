# Function: <code>pci_bus_read_config_byte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142da60)
Location: drivers/pci/access.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pcibios_set_master
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
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/iov.c:pci_iov_init
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/virtio/virtio_pci_modern.c:map_capability
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-agp.c:intel_8xx_fetch_size
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_fetch_size
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/via-agp.c:via_fetch_size
  - drivers/ata/libata-core.c:pci_test_config_bits
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_66_cable_detect
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/xen.c:xen_pcifront_enable_irq
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450nx
  - arch/x86/pci/fixup.c:pci_fixup_i450gx
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
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
**Symbols:**

```
ffffffff8142da60-ffffffff8142db00: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81478df0)
Location: drivers/pci/access.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
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
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/iov.c:pci_iov_init
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
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
ffffffff81478df0-ffffffff81478e90: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149a200)
Location: drivers/pci/access.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_irq
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:__pci_find_next_ht_cap
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
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
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/iov.c:pci_iov_init
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
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
ffffffff8149a200-ffffffff8149a2a0: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4305)
Location: drivers/pci/access.c:64
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_read_config_byte
Direct callers:
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff814a3e50-ffffffff814a3eaa: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3085)
Location: drivers/pci/access.c:64
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_read_config_byte
Direct callers:
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff814e2bc0-ffffffff814e2c20: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81512e25)
Location: drivers/pci/access.c:63
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_read_config_byte
Direct callers:
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff81512a20-ffffffff81512a80: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528280)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff81528280-ffffffff815282e0: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557510)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff81557510-ffffffff81557570: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578b40)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff81578b40-ffffffff81578ba0: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161db50)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff8161db50-ffffffff8161dbaf: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644370)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff81644370-ffffffff816443cf: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816270d0)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff816270d0-ffffffff8162712f: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816969a0)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff816969a0-ffffffff816969ff: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b78d0)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff817b78d0-ffffffff817b7948: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d20b0)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff818d20b0-ffffffff818d2128: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff819150b0)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff819150b0-ffffffff81915128: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195d020)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff8195d020-ffffffff8195d098: pci_bus_read_config_byte (STB_GLOBAL)
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
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106db758)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffff8000106db758-ffff8000106db86c: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0876c30)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
c0876c30-c0876cf4: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852030)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:early_read_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
c000000000852030-c000000000852120: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b35a4)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffe0004b35a4-ffffffe0004b3620: pci_bus_read_config_byte (STB_GLOBAL)
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
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d060)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff8156d060-ffffffff8156d0c0: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155b7d0)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff8155b7d0-ffffffff8155b830: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156c890)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff8156c890-ffffffff8156c8f0: pci_bus_read_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_bus_read_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81586d90)
Location: drivers/pci/access.c:63
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_bus_find_capability
  - drivers/pci/pci.c:__pci_find_next_cap_ttl
```
**Symbols:**

```
ffffffff81586d90-ffffffff81586df0: pci_bus_read_config_byte (STB_GLOBAL)
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
