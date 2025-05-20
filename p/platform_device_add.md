# Function: <code>platform_device_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154dae0)
Location: drivers/base/platform.c:325
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register
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
ffffffff8154dae0-ffffffff8154dd47: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8159f910)
Location: drivers/base/platform.c:345
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff8159f910-ffffffff8159fb6f: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815cdf50)
Location: drivers/base/platform.c:360
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff815cdf50-ffffffff815ce1af: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e2980)
Location: drivers/base/platform.c:360
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff815e2980-ffffffff815e2be2: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81649b30)
Location: drivers/base/platform.c:360
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81649b30-ffffffff81649d92: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816850f0)
Location: drivers/base/platform.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
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
ffffffff816850f0-ffffffff8168533f: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a4d50)
Location: drivers/base/platform.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
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
ffffffff816a4d50-ffffffff816a4fa2: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:398
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
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
ffffffff816de9bb-ffffffff816de9d5: platform_device_add.cold (STB_LOCAL)
ffffffff816ddd10-ffffffff816ddf59: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/base/platform.c:platform_device_register
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
ffffffff81702ba8-ffffffff81702bc2: platform_device_add.cold (STB_LOCAL)
ffffffff81701e70-ffffffff817020ad: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff817bceba-ffffffff817bced4: platform_device_add.cold (STB_LOCAL)
ffffffff817bb9f0-ffffffff817bbc2e: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:688
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff81c0e4df-ffffffff81c0e4f9: platform_device_add.cold (STB_LOCAL)
ffffffff817d0640-ffffffff817d087e: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:687
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff81c008df-ffffffff81c008f9: platform_device_add.cold (STB_LOCAL)
ffffffff817b4060-ffffffff817b429e: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:651
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/firmware/sysfb.c:sysfb_init
```
**Symbols:**

```
ffffffff81d032af-ffffffff81d032de: platform_device_add.cold (STB_LOCAL)
ffffffff8183d980-ffffffff8183dbcd: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:656
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/firmware/sysfb.c:sysfb_init
```
**Symbols:**

```
ffffffff81ecb9fe-ffffffff81ecba2c: platform_device_add.cold (STB_LOCAL)
ffffffff81980630-ffffffff8198089c: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:656
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/firmware/sysfb.c:sysfb_init
```
**Symbols:**

```
ffffffff820986e3-ffffffff820986f7: platform_device_add.cold (STB_LOCAL)
ffffffff81aee160-ffffffff81aee3af: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:656
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/firmware/sysfb.c:sysfb_init
```
**Symbols:**

```
ffffffff821196cf-ffffffff821196e3: platform_device_add.cold (STB_LOCAL)
ffffffff81b3c4f0-ffffffff81b3c762: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:657
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/firmware/sysfb.c:sysfb_init
  - drivers/firmware/sysfb_simplefb.c:sysfb_create_simplefb
```
**Symbols:**

```
ffffffff821f7692-ffffffff821f76a6: platform_device_add.cold (STB_LOCAL)
ffffffff81b94040-ffffffff81b942aa: platform_device_add (STB_GLOBAL)
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
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ed398)
Location: drivers/base/platform.c:475
Inline: False
Direct callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/acpi/arm64/iort.c:iort_add_platform_device
  - drivers/soc/imx/gpcv2.c:imx_gpcv2_probe
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/base/platform.c:platform_device_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffff8000108ed398-ffff8000108ed608: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09db280)
Location: drivers/base/platform.c:475
Inline: False
Direct callers:
  - arch/arm/mach-omap2/omap_device.c:omap_device_register
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_probe
  - drivers/soc/imx/gpc.c:imx_gpc_probe
  - drivers/soc/imx/gpcv2.c:imx_gpcv2_probe
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
c09db280-c09db4d8: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000985410)
Location: drivers/base/platform.c:475
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:add_pcspkr
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/base/platform.c:platform_device_register
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
c000000000985410-c000000000985774: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe000580556)
Location: drivers/base/platform.c:475
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/base/platform.c:platform_device_register
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
ffffffe000580556-ffffffe00058078e: platform_device_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/base/platform.c:platform_device_register
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816c82f8-ffffffff816c8312: platform_device_add.cold (STB_LOCAL)
ffffffff816c75c0-ffffffff816c77fd: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/base/platform.c:platform_device_register
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816a35f8-ffffffff816a3612: platform_device_add.cold (STB_LOCAL)
ffffffff816a28c0-ffffffff816a2afd: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/base/platform.c:platform_device_register
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
ffffffff816f6868-ffffffff816f6882: platform_device_add.cold (STB_LOCAL)
ffffffff816f5b30-ffffffff816f5d6d: platform_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int platform_device_add(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register
  - drivers/base/platform.c:platform_device_register
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
ffffffff81711108-ffffffff81711122: platform_device_add.cold (STB_LOCAL)
ffffffff817103c0-ffffffff817105fd: platform_device_add (STB_GLOBAL)
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
