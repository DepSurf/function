# Function: <code>platform_device_add_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154d9f0)
Location: drivers/base/platform.c:257
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
```
**Symbols:**

```
ffffffff8154d9f0-ffffffff8154da5e: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8159f820)
Location: drivers/base/platform.c:277
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8159f820-ffffffff8159f883: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815cde60)
Location: drivers/base/platform.c:292
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815cde60-ffffffff815cdec3: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e2890)
Location: drivers/base/platform.c:292
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815e2890-ffffffff815e28f3: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81649a40)
Location: drivers/base/platform.c:292
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81649a40-ffffffff81649aa3: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81685000)
Location: drivers/base/platform.c:291
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81685000-ffffffff81685063: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a4c60)
Location: drivers/base/platform.c:292
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816a4c60-ffffffff816a4cc4: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816ddc30)
Location: drivers/base/platform.c:330
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816ddc30-ffffffff816ddc91: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81701d90)
Location: drivers/base/platform.c:407
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81701d90-ffffffff81701df1: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bb910)
Location: drivers/base/platform.c:468
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff817bb910-ffffffff817bb971: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d0560)
Location: drivers/base/platform.c:620
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff817d0560-ffffffff817d05c1: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b3f80)
Location: drivers/base/platform.c:619
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff817b3f80-ffffffff817b3fe1: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183d460)
Location: drivers/base/platform.c:599
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff8183d460-ffffffff8183d4c1: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff819800e0)
Location: drivers/base/platform.c:604
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff819800e0-ffffffff8198014e: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aedab0)
Location: drivers/base/platform.c:604
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff81aedab0-ffffffff81aedb1e: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3be70)
Location: drivers/base/platform.c:604
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff81b3be70-ffffffff81b3bede: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b939c0)
Location: drivers/base/platform.c:605
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/firmware/sysfb_simplefb.c:sysfb_create_simplefb
```
**Symbols:**

```
ffffffff81b939c0-ffffffff81b93a2e: platform_device_add_resources (STB_GLOBAL)
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
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ed288)
Location: drivers/base/platform.c:407
Inline: False
Direct callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/acpi/arm64/iort.c:iort_add_platform_device
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffff8000108ed288-ffff8000108ed2f4: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09db1b0)
Location: drivers/base/platform.c:407
Inline: False
Direct callers:
  - arch/arm/mach-omap2/omap_device.c:omap_device_build
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
c09db1b0-c09db20c: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c0000000009852c0)
Location: drivers/base/platform.c:407
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
c0000000009852c0-c000000000985350: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe000580464)
Location: drivers/base/platform.c:407
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffe000580464-ffffffe0005804c8: platform_device_add_resources (STB_GLOBAL)
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
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c74e0)
Location: drivers/base/platform.c:407
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816c74e0-ffffffff816c7541: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a27e0)
Location: drivers/base/platform.c:407
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816a27e0-ffffffff816a2841: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f5a50)
Location: drivers/base/platform.c:407
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816f5a50-ffffffff816f5ab1: platform_device_add_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int platform_device_add_resources(struct platform_device *pdev, const struct resource *res, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817102e0)
Location: drivers/base/platform.c:407
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff817102e0-ffffffff81710341: platform_device_add_resources (STB_GLOBAL)
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
