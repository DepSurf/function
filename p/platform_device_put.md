# Function: <code>platform_device_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154d980)
Location: drivers/base/platform.c:201
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
```
**Symbols:**

```
ffffffff8154d980-ffffffff8154d99a: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815a046a)
Location: drivers/base/platform.c:221
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff8159f7b0-ffffffff8159f7ca: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815ceaaa)
Location: drivers/base/platform.c:236
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff815cddf0-ffffffff815cde0a: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e351c)
Location: drivers/base/platform.c:236
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff815e2820-ffffffff815e283b: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8164a6cc)
Location: drivers/base/platform.c:236
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff816499d0-ffffffff816499eb: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81685c3c)
Location: drivers/base/platform.c:235
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81684f90-ffffffff81684faa: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a58b9)
Location: drivers/base/platform.c:236
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816a4be0-ffffffff816a4c03: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816de889)
Location: drivers/base/platform.c:274
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816ddbb0-ffffffff816ddbd3: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81702b09)
Location: drivers/base/platform.c:351
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81701d10-ffffffff81701d33: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bcdc9)
Location: drivers/base/platform.c:412
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff817bb870-ffffffff817bb893: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1cb9)
Location: drivers/base/platform.c:564
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff817d0530-ffffffff817d0553: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b56e9)
Location: drivers/base/platform.c:563
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff817b3f50-ffffffff817b3f73: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183ebf9)
Location: drivers/base/platform.c:543
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/firmware/sysfb.c:sysfb_init
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff8183d430-ffffffff8183d453: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81981b0c)
Location: drivers/base/platform.c:548
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/firmware/sysfb.c:sysfb_init
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff819800b0-ffffffff819800df: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aef7cc)
Location: drivers/base/platform.c:548
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/firmware/sysfb.c:sysfb_init
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff81aeda70-ffffffff81aeda9f: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3dbac)
Location: drivers/base/platform.c:548
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/firmware/sysfb.c:sysfb_init
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff81b3be30-ffffffff81b3be5f: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b956ec)
Location: drivers/base/platform.c:549
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/firmware/sysfb.c:sysfb_init
  - drivers/firmware/sysfb_simplefb.c:sysfb_create_simplefb
```
**Symbols:**

```
ffffffff81b93980-ffffffff81b939af: platform_device_put (STB_GLOBAL)
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
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ee640)
Location: drivers/base/platform.c:351
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/acpi/arm64/iort.c:iort_add_platform_device
  - drivers/soc/imx/gpcv2.c:imx_gpcv2_probe
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/of/platform.c:of_platform_device_create_pdata
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
ffff8000108ed1d8-ffff8000108ed210: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09dc1a8)
Location: drivers/base/platform.c:351
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - arch/arm/mach-omap2/omap_device.c:omap_device_build
  - arch/arm/mach-omap2/hsmmc.c:omap_hsmmc_init
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_probe
  - drivers/soc/imx/gpc.c:imx_gpc_probe
  - drivers/soc/imx/gpcv2.c:imx_gpcv2_probe
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/of/platform.c:of_platform_device_create_pdata
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
c09db134-c09db164: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000987184)
Location: drivers/base/platform.c:351
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - arch/powerpc/kernel/setup-common.c:add_pcspkr
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/of/platform.c:of_platform_device_create_pdata
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
c0000000009851f0-c00000000098523c: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe00058159e)
Location: drivers/base/platform.c:351
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/of/platform.c:of_platform_device_create_pdata
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
ffffffe000580364-ffffffe000580398: platform_device_put (STB_GLOBAL)
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
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c8259)
Location: drivers/base/platform.c:351
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816c7460-ffffffff816c7483: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a3559)
Location: drivers/base/platform.c:351
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816a2760-ffffffff816a2783: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f67c9)
Location: drivers/base/platform.c:351
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816f59d0-ffffffff816f59f3: platform_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void platform_device_put(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81711069)
Location: drivers/base/platform.c:351
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81710260-ffffffff81710283: platform_device_put (STB_GLOBAL)
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
