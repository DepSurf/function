# Function: <code>pci_bus_write_config_byte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142dc60)
Location: drivers/pci/access.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:quirk_via_ioapic
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
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
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/htirq.c:__ht_create_irq
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/via-agp.c:via_cleanup
  - drivers/char/agp/via-agp.c:via_cleanup_agp3
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_piix_set
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff8142dc60-ffffffff8142dcc7: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81478ff0)
Location: drivers/pci/access.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_via_ioapic
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/htirq.c:__ht_create_irq
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/via-agp.c:via_cleanup_agp3
  - drivers/char/agp/via-agp.c:via_cleanup
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_piix_set
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff81478ff0-ffffffff81479057: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149a400)
Location: drivers/pci/access.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_unhide_mch_dev6
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_nvidia_ck804_pcie_aer_ext_cap
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_503
  - drivers/pci/quirks.c:quirk_sis_96x_smbus
  - drivers/pci/quirks.c:quirk_ide_samemode
  - drivers/pci/quirks.c:quirk_svwks_csb5ide
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_amd_ide_mode
  - drivers/pci/quirks.c:quirk_mediagx_master
  - drivers/pci/quirks.c:quirk_vt82c598_id
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/quirks.c:quirk_via_vt8237_bypass_apic_deassert
  - drivers/pci/quirks.c:quirk_via_ioapic
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/htirq.c:__ht_create_irq
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_820_cleanup
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_8xx_cleanup
  - drivers/char/agp/via-agp.c:via_cleanup_agp3
  - drivers/char/agp/via-agp.c:via_cleanup
  - drivers/char/agp/via-agp.c:via_configure
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_piix_set
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff8149a400-ffffffff8149a467: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a436d)
Location: drivers/pci/access.c:67
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
Direct callers:
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff814a3f90-ffffffff814a3fae: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e30fd)
Location: drivers/pci/access.c:67
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
Direct callers:
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff814e2d00-ffffffff814e2d24: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81512fc9)
Location: drivers/pci/access.c:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
Direct callers:
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff81512b60-ffffffff81512b84: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815283c0)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff815283c0-ffffffff815283e4: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557650)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff81557650-ffffffff81557674: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578c80)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff81578c80-ffffffff81578ca4: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161dc90)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff8161dc90-ffffffff8161dcb4: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816444b0)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff816444b0-ffffffff816444d4: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627210)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff81627210-ffffffff81627234: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81696ae0)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff81696ae0-ffffffff81696b04: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b7a70)
Location: drivers/pci/access.c:69
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff817b7a70-ffffffff817b7aa3: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d2280)
Location: drivers/pci/access.c:69
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff818d2280-ffffffff818d22b3: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81915280)
Location: drivers/pci/access.c:69
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff81915280-ffffffff819152b3: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195d1f0)
Location: drivers/pci/access.c:69
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff8195d1f0-ffffffff8195d223: pci_bus_write_config_byte (STB_GLOBAL)
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
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106db610)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffff8000106db610-ffff8000106db6ec: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0876e8c)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
```
**Symbols:**

```
c0876e8c-c0876f0c: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852380)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:early_write_config_byte
  - drivers/pci/access.c:pci_write_config_byte
```
**Symbols:**

```
c000000000852380-c000000000852430: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3734)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
```
**Symbols:**

```
ffffffe0004b3734-ffffffe0004b37a2: pci_bus_write_config_byte (STB_GLOBAL)
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
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d1a0)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff8156d1a0-ffffffff8156d1c4: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155b910)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff8155b910-ffffffff8155b934: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156c9d0)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff8156c9d0-ffffffff8156c9f4: pci_bus_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_bus_write_config_byte(struct pci_bus *bus, unsigned int devfn, int pos, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81586ed0)
Location: drivers/pci/access.c:66
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffffffff81586ed0-ffffffff81586ef4: pci_bus_write_config_byte (STB_GLOBAL)
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
