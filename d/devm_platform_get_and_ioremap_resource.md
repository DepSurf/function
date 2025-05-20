# Function: <code>devm_platform_get_and_ioremap_resource</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *devm_platform_get_and_ioremap_resource(struct platform_device *pdev, unsigned int index, struct resource **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bc5d5)
Location: drivers/base/platform.c:75
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_ioremap_resource
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff817bc640-ffffffff817bc6b5: devm_platform_get_and_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *devm_platform_get_and_ioremap_resource(struct platform_device *pdev, unsigned int index, struct resource **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1305)
Location: drivers/base/platform.c:97
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_ioremap_resource
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff817d1370-ffffffff817d13e5: devm_platform_get_and_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *devm_platform_get_and_ioremap_resource(struct platform_device *pdev, unsigned int index, struct resource **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b4d35)
Location: drivers/base/platform.c:97
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_ioremap_resource
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff817b4da0-ffffffff817b4e12: devm_platform_get_and_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *devm_platform_get_and_ioremap_resource(struct platform_device *pdev, unsigned int index, struct resource **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183e1f5)
Location: drivers/base/platform.c:97
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_ioremap_resource
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff8183e260-ffffffff8183e2d2: devm_platform_get_and_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *devm_platform_get_and_ioremap_resource(struct platform_device *pdev, unsigned int index, struct resource **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81981005)
Location: drivers/base/platform.c:99
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_ioremap_resource
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81981080-ffffffff81981101: devm_platform_get_and_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *devm_platform_get_and_ioremap_resource(struct platform_device *pdev, unsigned int index, struct resource **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aeebc5)
Location: drivers/base/platform.c:99
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_ioremap_resource
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81aeec50-ffffffff81aeecd1: devm_platform_get_and_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *devm_platform_get_and_ioremap_resource(struct platform_device *pdev, unsigned int index, struct resource **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3cfb5)
Location: drivers/base/platform.c:99
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_ioremap_resource
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81b3d040-ffffffff81b3d0c1: devm_platform_get_and_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *devm_platform_get_and_ioremap_resource(struct platform_device *pdev, unsigned int index, struct resource **res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b94af5)
Location: drivers/base/platform.c:99
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_ioremap_resource
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/reset/reset-simple.c:reset_simple_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81b94b80-ffffffff81b94c01: devm_platform_get_and_ioremap_resource (STB_GLOBAL)
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
