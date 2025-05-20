# Function: <code>inl</code>

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
In arch/x86/platform/atom/pmc_atom.c (ffffffff81078922)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_power_off
```
```
In lib/iomap.c (ffffffff81402742)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - lib/iomap.c:ioread32
  - lib/iomap.c:ioread32be
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a200)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143afdb)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_resource_io
```
```
In drivers/acpi/osl.c (ffffffff81479aaa)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814ac5b7)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ad625)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150c40b)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81630086)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81646b72)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff816d5276)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In arch/x86/pci/direct.c (ffffffff816f69b5)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf1_read
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
```
In arch/x86/pci/early.c (ffffffff816fa862)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_device
  - arch/x86/pci/early.c:early_dump_pci_devices
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
In arch/x86/platform/atom/pmc_atom.c (ffffffff81079e12)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_power_off
```
```
In lib/iomap.c (ffffffff8144a585)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81474f7e)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff81488484)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814c806f)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814fb918)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fd04e)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155e727)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81690cec)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816a76a6)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81739496)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In arch/x86/pci/direct.c (ffffffff81fe6293)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8175f9bd)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
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
In arch/x86/platform/atom/pmc_atom.c (ffffffff8107dbf2)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_power_off
```
```
In lib/iomap.c (ffffffff81468f45)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8149754e)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a9c64)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814e9f7f)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8151e5ec)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff8151fcd0)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158ad17)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bed9c)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d57c6)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff8176c6c6)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In arch/x86/pci/direct.c (ffffffff82024ad7)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8178befd)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e625)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a120b)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b41e7)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff814f5c3c)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8152f731)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/acpi/processor_throttling.c (ffffffff815312df)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159ef17)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816d365a)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816e99ad)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff8178aa56)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81799412)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff82107f7d)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff817aaea6)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a959)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814dfbce)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f39f7)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff8153657c)
Location: arch/x86/include/asm/io.h:350
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81591841)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/acpi/processor_throttling.c (ffffffff81592303)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8160440b)
Location: arch/x86/include/asm/io.h:350
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8173fd44)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8175619d)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81801096)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8180f7b2)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff827118c3)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81822396)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cfc06)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150ef8e)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff81523c1b)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff8156c1fd)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815c8b8a)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/acpi/processor_throttling.c (ffffffff815c9753)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163d673)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817806ee)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81796501)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff8184aca5)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81859955)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8273bbaf)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8186c598)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e4516)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815245fe)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff81539a7b)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff81583e2d)
Location: arch/x86/include/asm/io.h:344
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815e215a)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/acpi/processor_throttling.c (ffffffff815e2d33)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165b8f3)
Location: arch/x86/include/asm/io.h:344
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817a6f0e)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bce11)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81877b85)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81878bf5)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff828f5bc1)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8188c483)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510e75)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81552cce)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156939b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff815b4a04)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816140ea)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff816148c3)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81690f51)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817e611e)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fc007)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff818bc405)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff818bdec5)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8291160d)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff818d6dc3)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815318e5)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815742be)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff8158a3cb)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff815d5c84)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816355da)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff81635db3)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b3991)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81816fde)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182ce57)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff818eeed5)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff818f0a15)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8291b3a4)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81909143)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81595af5)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/pci/pci-sysfs.c (ffffffff8163154b)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff8167f814)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816e2079)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e2992)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81766cf1)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818e8061)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818fdb55)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/clocksource/acpi_pm.c (ffffffff819c2acf)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff819c5bd5)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff82d3110f)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81bb9a33)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b1585)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/pci/pci-sysfs.c (ffffffff81656beb)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff8169e2d4)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816fff43)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff81700612)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81781c31)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f1041)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81906435)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/clocksource/acpi_pm.c (ffffffff819c2f3f)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81c2d59c)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff83020099)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81bce333)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc395)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/pci/pci-sysfs.c (ffffffff8163965b)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff81681014)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816e1a63)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e310e)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8176548d)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d4841)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818e9a44)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/clocksource/acpi_pm.c (ffffffff819a737f)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81c1f819)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8322b28c)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81bc1cf3)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816231e5)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a9bfd)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff816f5fa4)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_port
```
```
In drivers/acpi/processor_idle.c (ffffffff81759f8d)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff8175baee)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e9be6)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8196f111)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff819860e4)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81a5486f)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81d3106b)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff83315a10)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81c92303)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e573c)
Location: arch/powerpc/include/asm/io-defs.h:25
Inline: True
```
```
In drivers/pci/pci-sysfs.c (c00000000086b798)
Location: arch/powerpc/include/asm/io-defs.h:25
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/tty/serial/8250/8250_pci.c (c00000000093a0dc)
Location: arch/powerpc/include/asm/io-defs.h:25
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (c000000000b191dc)
Location: arch/powerpc/include/asm/io-defs.h:25
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3d304)
Location: arch/powerpc/include/asm/io-defs.h:25
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529ec5)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157e25b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff815c99e4)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81604dca)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff8160554b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816793f1)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817cf3be)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e5237)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff818902a5)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81891d45)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff829000b3)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff818a8503)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8151a1a5)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155a8ce)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156d02b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff815b2a74)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815efa8b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff815f05e9)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816584e1)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817ad2ee)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81849565)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8184b0c5)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff828f86c2)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81862f13)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81525f55)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815685ee)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157e11b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff815c9f64)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816298ba)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff8162a093)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a77d1)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8180be5e)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81821cd7)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff818e3d05)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff818e5845)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff829156af)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff818f9b63)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f8d5)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8158250e)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff815985cb)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff815e3dc4)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8164375a)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff81643f33)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c1c31)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81825f6e)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183c3a7)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81900975)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_verified
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff819024a5)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8291c406)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8191acc3)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
</ul>

## Differences
