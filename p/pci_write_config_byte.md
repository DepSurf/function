# Function: <code>pci_write_config_byte</code>

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
In arch/x86/kernel/quirks.c (ffffffff81035518)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In drivers/pci/probe.c (ffffffff8142fd0d)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff81434aea)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
```
```
In drivers/pci/quirks.c (ffffffff81442eab)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
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
```
```
In drivers/pci/htirq.c (ffffffff8145553f)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - drivers/pci/htirq.c:__ht_create_irq
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150a34d)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/char/agp/intel-agp.c (ffffffff815202ee)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
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
```
```
In drivers/char/agp/via-agp.c (ffffffff81523038)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_cleanup
  - drivers/char/agp/via-agp.c:via_cleanup_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
```
In drivers/ata/ata_piix.c (ffffffff815e2cea)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
```
```
In drivers/ata/pata_sis.c (ffffffff815e3b9b)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81630a7b)
Location: include/linux/pci.h:919
Inline: True
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8163ce10)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816455f5)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
```
```
In drivers/hwmon/hwmon.c (ffffffff81fb2c9d)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/fixup.c (ffffffff816f852d)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
```
```
In arch/x86/pci/irq.c (ffffffff816f9366)
Location: include/linux/pci.h:919
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:write_config_nybble
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_piix_set
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In arch/x86/kernel/quirks.c (ffffffff81034718)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In drivers/pci/probe.c (ffffffff8147b473)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff8148045a)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
```
```
In drivers/pci/quirks.c (ffffffff81490ba9)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
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
```
```
In drivers/pci/htirq.c (ffffffff814a217f)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - drivers/pci/htirq.c:__ht_create_irq
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155ca12)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/char/agp/intel-agp.c (ffffffff815731c0)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
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
```
```
In drivers/char/agp/via-agp.c (ffffffff81575fac)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_cleanup_agp3
  - drivers/char/agp/via-agp.c:via_cleanup
  - drivers/char/agp/via-agp.c:via_configure
```
```
In drivers/ata/ata_piix.c (ffffffff8163cc4e)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
```
```
In drivers/ata/pata_sis.c (ffffffff8163e5b3)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816916dc)
Location: include/linux/pci.h:930
Inline: True
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8169da18)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aa670)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
```
```
In drivers/hwmon/hwmon.c (ffffffff81fdf86d)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/fixup.c (ffffffff8175d289)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
```
```
In arch/x86/pci/irq.c (ffffffff8175ec4c)
Location: include/linux/pci.h:930
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_piix_set
  - arch/x86/pci/irq.c:write_config_nybble
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
In arch/x86/kernel/quirks.c (ffffffff81034358)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
```
```
In drivers/pci/probe.c (ffffffff8149c8f3)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff814a1aaa)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
```
```
In drivers/pci/quirks.c (ffffffff814b23f9)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
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
```
```
In drivers/pci/htirq.c (ffffffff814c3dcf)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - drivers/pci/htirq.c:__ht_create_irq
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81589352)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/char/agp/intel-agp.c (ffffffff8159f830)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
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
```
```
In drivers/char/agp/via-agp.c (ffffffff815a263c)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_cleanup_agp3
  - drivers/char/agp/via-agp.c:via_cleanup
  - drivers/char/agp/via-agp.c:via_configure
```
```
In drivers/ata/ata_piix.c (ffffffff8166dcce)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:do_pata_set_dmamode
  - drivers/ata/ata_piix.c:piix_set_timings
  - drivers/ata/ata_piix.c:piix_set_timings
```
```
In drivers/ata/pata_sis.c (ffffffff8166f623)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bf78c)
Location: include/linux/pci.h:960
Inline: True
```
```
In drivers/usb/host/ehci-pci.c (ffffffff816cbb25)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d87b0)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
```
```
In drivers/hwmon/hwmon.c (ffffffff8201d4d8)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_init
```
```
In arch/x86/pci/fixup.c (ffffffff817897b9)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
```
```
In arch/x86/pci/irq.c (ffffffff8178b17c)
Location: include/linux/pci.h:960
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis_set
  - arch/x86/pci/irq.c:pirq_piix_set
  - arch/x86/pci/irq.c:write_config_nybble
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4350)
Location: drivers/pci/access.c:934
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pcibios_update_irq
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
ffffffff814a4350-ffffffff814a438e: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e30e0)
Location: drivers/pci/access.c:934
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
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
ffffffff814e30e0-ffffffff814e3124: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81512fb0)
Location: drivers/pci/access.c:567
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
ffffffff81512fb0-ffffffff81512ff5: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528700)
Location: drivers/pci/access.c:567
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
ffffffff81528700-ffffffff8152872d: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557990)
Location: drivers/pci/access.c:567
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:program_hpp_type0
  - drivers/pci/probe.c:program_hpp_type0
  - drivers/pci/probe.c:program_hpp_type0
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
ffffffff81557990-ffffffff815579bf: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81578fc0)
Location: drivers/pci/access.c:558
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
ffffffff81578fc0-ffffffff81578fef: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161dfd0)
Location: drivers/pci/access.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
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
ffffffff8161dfd0-ffffffff8161dfff: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816447f0)
Location: drivers/pci/access.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
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
ffffffff816447f0-ffffffff8164481f: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627570)
Location: drivers/pci/access.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
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
ffffffff81627570-ffffffff8162759f: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81696dc0)
Location: drivers/pci/access.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
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
  - arch/x86/pci/irq.c:pirq_ib_set
  - arch/x86/pci/irq.c:pirq_piix_set
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff81696dc0-ffffffff81696def: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b7de0)
Location: drivers/pci/access.c:559
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis503_set
  - arch/x86/pci/irq.c:pirq_sis497_set
  - arch/x86/pci/irq.c:pirq_ib_set
  - arch/x86/pci/irq.c:pirq_piix_set
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff817b7de0-ffffffff817b7e25: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d2690)
Location: drivers/pci/access.c:565
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis503_set
  - arch/x86/pci/irq.c:pirq_sis497_set
  - arch/x86/pci/irq.c:pirq_ib_set
  - arch/x86/pci/irq.c:pirq_piix_set
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff818d2690-ffffffff818d26d5: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81915690)
Location: drivers/pci/access.c:579
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis503_set
  - arch/x86/pci/irq.c:pirq_sis497_set
  - arch/x86/pci/irq.c:pirq_ib_set
  - arch/x86/pci/irq.c:pirq_piix_set
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff81915690-ffffffff819156d5: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195d600)
Location: drivers/pci/access.c:577
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - arch/x86/kernel/quirks.c:quirk_intel_irqbalance
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/quirks.c:asus_hides_ac97_lpc
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_fixup
  - drivers/ata/pata_sis.c:sis_133_early_set_dmamode
  - drivers/ata/pata_sis.c:sis_100_set_dmamode
  - drivers/ata/pata_sis.c:sis_133_set_piomode
  - drivers/ata/pata_sis.c:sis_100_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_old_set_piomode
  - drivers/ata/pata_sis.c:sis_pre_reset
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/fixup.c:pci_early_fixup_cyrix_5530
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/fixup.c:pci_fixup_via_northbridge_bug
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_sis503_set
  - arch/x86/pci/irq.c:pirq_sis497_set
  - arch/x86/pci/irq.c:pirq_ib_set
  - arch/x86/pci/irq.c:pirq_piix_set
  - arch/x86/pci/irq.c:write_config_nybble
```
**Symbols:**

```
ffffffff8195d600-ffffffff8195d645: pci_write_config_byte (STB_GLOBAL)
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
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106db6f0)
Location: drivers/pci/access.c:558
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
```
**Symbols:**

```
ffff8000106db6f0-ffff8000106db758: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c08772b8)
Location: drivers/pci/access.c:558
Inline: False
Direct callers:
  - arch/arm/kernel/bios32.c:pcibios_fixup_bus
  - arch/arm/kernel/bios32.c:pci_fixup_83c553
  - arch/arm/kernel/bios32.c:pci_fixup_83c553
  - arch/arm/kernel/bios32.c:pci_fixup_83c553
  - arch/arm/kernel/bios32.c:pci_fixup_83c553
  - arch/arm/kernel/bios32.c:pci_fixup_83c553
  - arch/arm/kernel/bios32.c:pci_fixup_83c553
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
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
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
```
**Symbols:**

```
c08772b8-c08772f8: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852920)
Location: drivers/pci/access.c:558
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
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
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
```
**Symbols:**

```
c000000000852920-c000000000852968: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3c1e)
Location: drivers/pci/access.c:558
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
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
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
```
**Symbols:**

```
ffffffe0004b3c1e-ffffffe0004b3c68: pci_write_config_byte (STB_GLOBAL)
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
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d4e0)
Location: drivers/pci/access.c:558
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
ffffffff8156d4e0-ffffffff8156d50f: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155bc50)
Location: drivers/pci/access.c:558
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
ffffffff8155bc50-ffffffff8155bc7f: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156cd10)
Location: drivers/pci/access.c:558
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
ffffffff8156cd10-ffffffff8156cd3f: pci_write_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_write_config_byte(const struct pci_dev *dev, int where, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587210)
Location: drivers/pci/access.c:558
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
  - drivers/pci/pci-acpi.c:program_hpx_type0
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_init
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
ffffffff81587210-ffffffff8158723f: pci_write_config_byte (STB_GLOBAL)
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
