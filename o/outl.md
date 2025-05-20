# Function: <code>outl</code>

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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81024571)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/platform/atom/pmc_atom.c (ffffffff81078926)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_power_off
```
```
In lib/iomap.c (ffffffff81402802)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a231)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143afbb)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_resource_io
```
```
In drivers/acpi/osl.c (ffffffff81479af0)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ad707)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150c40c)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81630059)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81649a6b)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In arch/x86/pci/direct.c (ffffffff816f6943)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf1_read
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
```
In arch/x86/pci/early.c (ffffffff816fa835)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config_16
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:early_dump_pci_device
  - arch/x86/pci/early.c:early_dump_pci_devices
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81023831)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/platform/atom/pmc_atom.c (ffffffff81079e19)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_power_off
```
```
In lib/iomap.c (ffffffff8144a5c9)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81474f82)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff81488461)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814c80b5)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fd056)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155e72b)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81690cb0)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aa4dd)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In arch/x86/pci/direct.c (ffffffff81fe629c)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8175f9a8)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:read_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81023f61)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In arch/x86/platform/atom/pmc_atom.c (ffffffff8107dbf9)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_power_off
```
```
In lib/iomap.c (ffffffff81468f89)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81497552)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a9c41)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814e9fc5)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8151fcd8)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158ad1b)
Location: arch/x86/include/asm/io.h:318
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bed60)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d861d)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In arch/x86/pci/direct.c (ffffffff82024ae0)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8178bee8)
Location: arch/x86/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:read_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101b772)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8146e669)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a120f)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b400c)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/acpi/osl.c (ffffffff814f5c88)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff815312e7)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159ef1b)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816d361e)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ecb0d)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81799419)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff82107f86)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff817aae8e)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:read_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101c452)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8149a99d)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814dfbd2)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f3818)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/acpi/osl.c (ffffffff815365c8)
Location: arch/x86/include/asm/io.h:350
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8159230b)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8160440f)
Location: arch/x86/include/asm/io.h:350
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8173fcf6)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81759303)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8180f7b9)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff827118cc)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8182237e)
Location: arch/x86/include/asm/io.h:350
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:read_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ce55)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff814cfc53)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150ef8f)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff81523a21)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/acpi/osl.c (ffffffff8156c23b)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff815c975b)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163d674)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817806b4)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817993c9)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81859959)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8273bbb8)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8186c590)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:read_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101cade)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff814e4563)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815245ff)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff81539881)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/acpi/osl.c (ffffffff81583e6b)
Location: arch/x86/include/asm/io.h:344
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff815e2d3b)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165b8f4)
Location: arch/x86/include/asm/io.h:344
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817a6ed4)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bfd39)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81878bf9)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff828f5bca)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8188c670)
Location: arch/x86/include/asm/io.h:344
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101e61e)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81510f2b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81552ccf)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff815691a2)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/acpi/osl.c (ffffffff815b4a41)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff816148cb)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81690f52)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817e60e4)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817ff5ec)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff818bdec9)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff82911616)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff818d6fbb)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ef9e)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8153199b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815742bf)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff8158a1e1)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815d5cc1)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81635dbb)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b3992)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81816fa4)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183044c)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff818f0a19)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8291b3ad)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8190933b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff810215ae)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81595e45)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/pci/pci-sysfs.c (ffffffff816312d0)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8167f851)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e299a)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81766cf2)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818e8027)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190132c)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff819c5bd9)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff82d31117)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81bb9c18)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81021d6e)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff815b18d5)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/pci/pci-sysfs.c (ffffffff81656970)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8169e311)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8170061a)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81781c32)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f1007)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81909bfc)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81c2d5a0)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff830200a1)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81bce518)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff810240fe)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff815bc6e5)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/pci/pci-sysfs.c (ffffffff81639590)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81681051)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e3116)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8176548e)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d4807)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ee31c)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81c1f81d)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8322b295)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81bc1eca)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff810284c2)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81623535)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a9a7c)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff816f6131)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8175baf6)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e9be7)
Location: arch/x86/include/asm/io.h:336
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8196f0d7)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8198aaec)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81d3106f)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff83315a19)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81c924da)
Location: arch/x86/include/asm/io.h:336
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In lib/iomap.c (c0000000007e5294)
Location: arch/powerpc/include/asm/io-defs.h:28
Inline: True
```
```
In drivers/pci/pci-sysfs.c (c00000000086b5c8)
Location: arch/powerpc/include/asm/io-defs.h:28
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (c00000000093a108)
Location: arch/powerpc/include/asm/io-defs.h:28
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (c000000000b19150)
Location: arch/powerpc/include/asm/io-defs.h:28
Inline: True
Inline callers:
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
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3781c)
Location: arch/powerpc/include/asm/io-defs.h:28
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:configure_hc
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101f0fe)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81529f7b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157e071)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815c9a21)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81605553)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816793f2)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817cf384)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e882c)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81891d49)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff829000bc)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff818a86fb)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In lib/iomap.c (ffffffff8151a25b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155a8cf)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156ce41)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815b2ab1)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff815f05f1)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816584e2)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817ad2b4)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8184b0c9)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff828f86cb)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8186310b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ef5e)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8152600b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815685ef)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157df31)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815c9fa1)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8162a09b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a77d2)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8180be24)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818252cc)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff818e5849)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff829156b8)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff818f9d5b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101f1ae)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8153f98b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8158250f)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pci/pci-sysfs.c (ffffffff815983e1)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815e3e01)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81643f3b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c1c32)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81825f34)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183ad0c)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff819024a9)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8291c40f)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8191aebb)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:read_pci_config
```
</details>
</li>
</ul>

## Differences
