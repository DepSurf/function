# Function: <code>device_create_managed_software_node</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_create_managed_software_node(struct device *dev, const struct property_entry *properties, const struct software_node *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bc2c0)
Location: drivers/base/swnode.c:1099
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
**Symbols:**

```
ffffffff817bc2c0-ffffffff817bc34b: device_create_managed_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_create_managed_software_node(struct device *dev, const struct property_entry *properties, const struct software_node *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81846b90)
Location: drivers/base/swnode.c:1102
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:platform_device_register_full
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff81846b90-ffffffff81846c3f: device_create_managed_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_create_managed_software_node(struct device *dev, const struct property_entry *properties, const struct software_node *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198b4c0)
Location: drivers/base/swnode.c:1096
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_huawei_pcie_sva
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:platform_device_register_full
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff8198b4c0-ffffffff8198b5a9: device_create_managed_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_create_managed_software_node(struct device *dev, const struct property_entry *properties, const struct software_node *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81afa9e0)
Location: drivers/base/swnode.c:1096
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_huawei_pcie_sva
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:platform_device_register_full
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff81afa9e0-ffffffff81afaac9: device_create_managed_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_create_managed_software_node(struct device *dev, const struct property_entry *properties, const struct software_node *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b48dd0)
Location: drivers/base/swnode.c:1035
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_huawei_pcie_sva
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:platform_device_register_full
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff81b48dd0-ffffffff81b48eb9: device_create_managed_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_create_managed_software_node(struct device *dev, const struct property_entry *properties, const struct software_node *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba11c0)
Location: drivers/base/swnode.c:1038
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_huawei_pcie_sva
  - drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add
  - drivers/base/platform.c:platform_device_register_full
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff81ba11c0-ffffffff81ba12a9: device_create_managed_software_node (STB_GLOBAL)
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
