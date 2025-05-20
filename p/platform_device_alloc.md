# Function: <code>platform_device_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154e460)
Location: drivers/base/platform.c:229
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:__platform_create_bundle
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
ffffffff8154e460-ffffffff8154e4d1: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815a0260)
Location: drivers/base/platform.c:249
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff815a0260-ffffffff815a02d1: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815ce8a0)
Location: drivers/base/platform.c:264
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff815ce8a0-ffffffff815ce911: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e3330)
Location: drivers/base/platform.c:264
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff815e3330-ffffffff815e33a1: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8164a4e0)
Location: drivers/base/platform.c:264
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff8164a4e0-ffffffff8164a551: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81685a50)
Location: drivers/base/platform.c:263
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
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
ffffffff81685a50-ffffffff81685ac1: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a56b0)
Location: drivers/base/platform.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
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
ffffffff816a56b0-ffffffff816a5721: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816de640)
Location: drivers/base/platform.c:302
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
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
ffffffff816de640-ffffffff816de6b4: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817028b0)
Location: drivers/base/platform.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
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
ffffffff817028b0-ffffffff81702966: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bc3f0)
Location: drivers/base/platform.c:440
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
ffffffff817bc3f0-ffffffff817bc4b6: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1020)
Location: drivers/base/platform.c:592
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
ffffffff817d1020-ffffffff817d10e6: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b4a40)
Location: drivers/base/platform.c:591
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
ffffffff817b4a40-ffffffff817b4b06: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183df30)
Location: drivers/base/platform.c:571
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
ffffffff8183df30-ffffffff8183dff6: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81980d20)
Location: drivers/base/platform.c:576
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
ffffffff81980d20-ffffffff81980df9: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aee8b0)
Location: drivers/base/platform.c:576
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
ffffffff81aee8b0-ffffffff81aee989: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3cc70)
Location: drivers/base/platform.c:576
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
ffffffff81b3cc70-ffffffff81b3cd7d: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b947a0)
Location: drivers/base/platform.c:577
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
ffffffff81b947a0-ffffffff81b948ad: platform_device_alloc (STB_GLOBAL)
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
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ee260)
Location: drivers/base/platform.c:379
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
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
ffff8000108ee260-ffff8000108ee31c: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09dbf84)
Location: drivers/base/platform.c:379
Inline: False
Direct callers:
  - arch/arm/mach-omap2/omap_device.c:omap_device_build
  - arch/arm/mach-omap2/hsmmc.c:omap_hsmmc_init
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_probe
  - drivers/soc/imx/gpc.c:imx_gpc_probe
  - drivers/soc/imx/gpcv2.c:imx_gpcv2_probe
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
c09dbf84-c09dc034: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000986e30)
Location: drivers/base/platform.c:379
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:add_pcspkr
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
c000000000986e30-c000000000986f38: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe000581386)
Location: drivers/base/platform.c:379
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
ffffffe000581386-ffffffe000581436: platform_device_alloc (STB_GLOBAL)
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
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c8000)
Location: drivers/base/platform.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816c8000-ffffffff816c80b6: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a3300)
Location: drivers/base/platform.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816a3300-ffffffff816a33b6: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f6570)
Location: drivers/base/platform.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
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
ffffffff816f6570-ffffffff816f6626: platform_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct platform_device *platform_device_alloc(const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81710e10)
Location: drivers/base/platform.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/pmem.c:register_e820_pmem
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/apei/hest.c:hest_parse_ghes
  - drivers/regulator/dummy.c:regulator_dummy_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
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
ffffffff81710e10-ffffffff81710ec6: platform_device_alloc (STB_GLOBAL)
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
