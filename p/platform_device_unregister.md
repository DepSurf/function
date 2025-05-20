# Function: <code>platform_device_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154ddf0)
Location: drivers/base/platform.c:455
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_unregister
  - drivers/usb/dwc2/pci.c:dwc2_pci_remove
  - drivers/input/serio/i8042.c:i8042_exit
```
**Symbols:**

```
ffffffff8154ddf0-ffffffff8154de13: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815a0561)
Location: drivers/base/platform.c:475
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/input/serio/i8042.c:i8042_exit
```
**Symbols:**

```
ffffffff8159fc00-ffffffff8159fc23: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815ceba1)
Location: drivers/base/platform.c:489
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/input/serio/i8042.c:i8042_exit
```
**Symbols:**

```
ffffffff815ce240-ffffffff815ce263: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e31a0)
Location: drivers/base/platform.c:489
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/input/serio/i8042.c:i8042_exit
```
**Symbols:**

```
ffffffff815e31a0-ffffffff815e31c5: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8164a350)
Location: drivers/base/platform.c:489
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/input/serio/i8042.c:i8042_exit
```
**Symbols:**

```
ffffffff8164a350-ffffffff8164a375: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81685760)
Location: drivers/base/platform.c:488
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/serio/i8042.c:i8042_exit
```
**Symbols:**

```
ffffffff81685760-ffffffff81685784: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a53c0)
Location: drivers/base/platform.c:488
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
**Symbols:**

```
ffffffff816a53c0-ffffffff816a53ed: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816de350)
Location: drivers/base/platform.c:528
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit
```
**Symbols:**

```
ffffffff816de350-ffffffff816de37d: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81702540)
Location: drivers/base/platform.c:606
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit
```
**Symbols:**

```
ffffffff81702540-ffffffff8170256d: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bc580)
Location: drivers/base/platform.c:667
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit
```
**Symbols:**

```
ffffffff817bc6c0-ffffffff817bc6f0: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d11b0)
Location: drivers/base/platform.c:819
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit
```
**Symbols:**

```
ffffffff817d12d0-ffffffff817d1300: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b4bd1)
Location: drivers/base/platform.c:818
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit
```
**Symbols:**

```
ffffffff817b4d00-ffffffff817b4d30: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183e1a1)
Location: drivers/base/platform.c:782
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_exit
```
**Symbols:**

```
ffffffff8183e2e0-ffffffff8183e310: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81980fa8)
Location: drivers/base/platform.c:791
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/video/fbdev/core/fbmem.c:do_remove_conflicting_framebuffers
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/firmware/sysfb.c:sysfb_disable
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_exit
```
**Symbols:**

```
ffffffff81981110-ffffffff8198114c: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aeeb58)
Location: drivers/base/platform.c:791
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/video/aperture.c:aperture_detach_platform_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/firmware/sysfb.c:sysfb_disable
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81aeecf0-ffffffff81aeed2c: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3cf48)
Location: drivers/base/platform.c:791
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/video/aperture.c:aperture_detach_platform_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/firmware/sysfb.c:sysfb_disable
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81b3d0e0-ffffffff81b3d11c: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b94a88)
Location: drivers/base/platform.c:791
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/video/aperture.c:aperture_detach_platform_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/firmware/sysfb.c:sysfb_disable
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81b94c20-ffffffff81b94c5c: platform_device_unregister (STB_GLOBAL)
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
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108edee8)
Location: drivers/base/platform.c:606
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_remove_subdev
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/firmware/raspberrypi.c:rpi_firmware_remove
  - drivers/firmware/raspberrypi.c:rpi_firmware_remove
```
**Symbols:**

```
ffff8000108edee8-ffff8000108edf28: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09dbd54)
Location: drivers/base/platform.c:606
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/pstore/ram.c:ramoops_exit
  - fs/pstore/ram.c:ramoops_init
  - fs/pstore/ram.c:ramoops_init
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/sm501.c:sm501_dev_remove
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/mfd/omap-usb-host.c:usbhs_omap_remove_child
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_unregister
  - drivers/usb/dwc2/pci.c:dwc2_pci_remove
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - sound/soc/soc-utils.c:snd_soc_util_exit
  - sound/soc/soc-utils.c:snd_soc_util_init
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_remove
```
**Symbols:**

```
c09dbd54-c09dbd88: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c0000000009865f0)
Location: drivers/base/platform.c:606
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/serio/i8042.c:i8042_exit
```
**Symbols:**

```
c0000000009865f0-c000000000986648: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe00058112a)
Location: drivers/base/platform.c:606
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/edac/sifive_edac.c:sifive_edac_exit
  - drivers/edac/sifive_edac.c:sifive_edac_init
```
**Symbols:**

```
ffffffe00058112a-ffffffe000581168: platform_device_unregister (STB_GLOBAL)
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
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c7c90)
Location: drivers/base/platform.c:606
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit
```
**Symbols:**

```
ffffffff816c7c90-ffffffff816c7cbd: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a2f90)
Location: drivers/base/platform.c:606
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit
```
**Symbols:**

```
ffffffff816a2f90-ffffffff816a2fbd: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f6200)
Location: drivers/base/platform.c:606
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit
```
**Symbols:**

```
ffffffff816f6200-ffffffff816f622d: platform_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81710a90)
Location: drivers/base/platform.c:606
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/ezx-pcap.c:pcap_remove_subdev
  - drivers/mfd/da903x.c:__remove_subdev
  - drivers/mfd/adp5520.c:__remove_subdev
  - drivers/mfd/tps6586x.c:__remove_subdev
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit
```
**Symbols:**

```
ffffffff81710a90-ffffffff81710abd: platform_device_unregister (STB_GLOBAL)
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
