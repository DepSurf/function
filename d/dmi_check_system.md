# Function: <code>dmi_check_system</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff816cf120)
Location: drivers/firmware/dmi_scan.c:783
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/ac.c:acpi_ac_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
```
**Symbols:**

```
ffffffff816cf120-ffffffff816cf173: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81732490)
Location: drivers/firmware/dmi_scan.c:805
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/ac.c:acpi_ac_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81732490-ffffffff817324e3: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81765460)
Location: drivers/firmware/dmi_scan.c:805
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/ac.c:acpi_ac_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81765460-ffffffff817654b3: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81783c70)
Location: drivers/firmware/dmi_scan.c:830
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/ac.c:acpi_ac_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81783c70-ffffffff81783cc3: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff817fa040)
Location: drivers/firmware/dmi_scan.c:830
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/ac.c:acpi_ac_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff817fa040-ffffffff817fa096: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818437a0)
Location: drivers/firmware/dmi_scan.c:846
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff818437a0-ffffffff818437f6: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8186f760)
Location: drivers/firmware/dmi_scan.c:846
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff8186f760-ffffffff8186f7b6: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818b3a10)
Location: drivers/firmware/dmi_scan.c:849
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff818b3a10-ffffffff818b3a66: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818e6330)
Location: drivers/firmware/dmi_scan.c:849
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/iommu/amd_iommu_quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff818e6330-ffffffff818e6386: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819b98f0)
Location: drivers/firmware/dmi_scan.c:885
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:do_prt_fixups
  - drivers/acpi/pci_irq.c:do_prt_fixups
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_broken_suspend
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff819b98f0-ffffffff819b9946: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819bbd60)
Location: drivers/firmware/dmi_scan.c:885
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:do_prt_fixups
  - drivers/acpi/pci_irq.c:do_prt_fixups
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_broken_suspend
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff819bbd60-ffffffff819bbdb6: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819a0560)
Location: drivers/firmware/dmi_scan.c:886
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:do_prt_fixups
  - drivers/acpi/pci_irq.c:do_prt_fixups
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff819a0560-ffffffff819a05b6: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81a4d440)
Location: drivers/firmware/dmi_scan.c:886
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:do_prt_fixups
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81a4d440-ffffffff81a4d496: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81bbbcd0)
Location: drivers/firmware/dmi_scan.c:886
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:do_prt_fixups
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81bbbcd0-ffffffff81bbbd2c: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81d614c0)
Location: drivers/firmware/dmi_scan.c:892
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:do_prt_fixups
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/acpi/x86/s2idle.c:acpi_s2idle_setup
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81d614c0-ffffffff81d6151c: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81dcc590)
Location: drivers/firmware/dmi_scan.c:892
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:do_prt_fixups
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81dcc590-ffffffff81dcc5ec: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81e850d0)
Location: drivers/firmware/dmi_scan.c:892
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:do_prt_fixups
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/x86/utils.c:acpi_proc_quirk_mwait_check
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/iommu/amd/quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/input/serio/i8042.c:i8042_pnp_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/pci/fixup.c:pci_fixup_msi_k8t_onboard_sound
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81e850d0-ffffffff81e8512c: dmi_check_system (STB_GLOBAL)
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
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffff800010b4db10)
Location: drivers/firmware/dmi_scan.c:849
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffff800010b4db10-ffff800010b4db80: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (c0c34b94)
Location: drivers/firmware/dmi_scan.c:849
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
c0c34b94-c0c34c04: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: include/linux/dmi.h:119
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (0)
Location: include/linux/dmi.h:119
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/dmi.h:119
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: include/linux/dmi.h:119
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/dmi.h:119
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (0)
Location: include/linux/dmi.h:119
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/dmi.h:119
Inline: True
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
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818890b0)
Location: drivers/firmware/dmi_scan.c:849
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/iommu/amd_iommu_quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff818890b0-ffffffff81889106: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81840a30)
Location: drivers/firmware/dmi_scan.c:849
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/iommu/amd_iommu_quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81840a30-ffffffff81840a86: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818db190)
Location: drivers/firmware/dmi_scan.c:849
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/iommu/amd_iommu_quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff818db190-ffffffff818db1e6: dmi_check_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dmi_check_system(const struct dmi_system_id *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818f7cb0)
Location: drivers/firmware/dmi_scan.c:849
Inline: False
Direct callers:
  - arch/x86/kernel/io_delay.c:io_delay_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/reboot.c:reboot_init
  - arch/x86/kernel/apic/apic.c:apic_is_clustered_box
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/sysfb_efi.c:sysfb_apply_efi_quirks
  - arch/x86/kernel/mmconf-fam10h_64.c:check_enable_amd_mmconf_dmi
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/pci_slot.c:acpi_pci_slot_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/iommu/amd_iommu_quirks.c:amd_iommu_apply_ivrs_quirks
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/keyboard/atkbd.c:atkbd_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/common.c:dmi_check_skip_isa_align
  - arch/x86/pci/common.c:dmi_check_pciprobe
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff818f7cb0-ffffffff818f7d06: dmi_check_system (STB_GLOBAL)
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
