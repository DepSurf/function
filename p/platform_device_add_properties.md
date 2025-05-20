# Function: <code>platform_device_add_properties</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_set *pset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154dac0)
Location: drivers/base/platform.c:311
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8154dac0-ffffffff8154dad4: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815a03c0)
Location: drivers/base/platform.c:331
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8159f8f0-ffffffff8159f904: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815cea00)
Location: drivers/base/platform.c:346
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815cdf30-ffffffff815cdf44: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e3492)
Location: drivers/base/platform.c:346
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815e2960-ffffffff815e2974: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8164a642)
Location: drivers/base/platform.c:346
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81649b10-ffffffff81649b24: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81685b81)
Location: drivers/base/platform.c:345
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff816850d0-ffffffff816850e4: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a57e7)
Location: drivers/base/platform.c:346
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff816a4d30-ffffffff816a4d44: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816de7a2)
Location: drivers/base/platform.c:384
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff816ddcf0-ffffffff816ddd04: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81702a22)
Location: drivers/base/platform.c:461
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81701e50-ffffffff81701e64: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bcce2)
Location: drivers/base/platform.c:522
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff817bb9d0-ffffffff817bb9e4: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1bd2)
Location: drivers/base/platform.c:674
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff817d0620-ffffffff817d0634: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b55fe)
Location: drivers/base/platform.c:673
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
```
**Symbols:**

```
ffffffff817b4040-ffffffff817b4054: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ee3d8)
Location: drivers/base/platform.c:461
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffff8000108ed360-ffff8000108ed394: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09dc0fc)
Location: drivers/base/platform.c:461
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - arch/arm/mach-tegra/board-paz00.c:tegra_paz00_wifikill_init
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
c09db260-c09db280: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000987028)
Location: drivers/base/platform.c:461
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
c0000000009853d0-c000000000985408: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe0005814e4)
Location: drivers/base/platform.c:461
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffe000580522-ffffffe000580556: platform_device_add_properties (STB_GLOBAL)
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
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c8172)
Location: drivers/base/platform.c:461
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816c75a0-ffffffff816c75b4: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a3472)
Location: drivers/base/platform.c:461
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816a28a0-ffffffff816a28b4: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f66e2)
Location: drivers/base/platform.c:461
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff816f5b10-ffffffff816f5b24: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int platform_device_add_properties(struct platform_device *pdev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81710f82)
Location: drivers/base/platform.c:461
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_register_full
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff817103a0-ffffffff817103b4: platform_device_add_properties (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct property_entry *properties</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct property_set *pset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct property_entry *properties</code> ➡️ <code>const struct property_entry *properties</code>
</li>
</ul>
</details>
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
