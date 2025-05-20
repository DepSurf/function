# Function: <code>usb_disabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81602f00)
Location: drivers/usb/core/usb.c:62
Inline: True
Direct callers:
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff81602f00-ffffffff81602f12: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81662bc0)
Location: drivers/usb/core/usb.c:58
Inline: True
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff81662bc0-ffffffff81662bd2: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816909b0)
Location: drivers/usb/core/usb.c:61
Inline: True
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff816909b0-ffffffff816909c2: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816a5cb0)
Location: drivers/usb/core/usb.c:61
Inline: True
Direct callers:
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff816a5cb0-ffffffff816a5cc2: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81711080)
Location: drivers/usb/core/usb.c:61
Inline: True
Direct callers:
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff81711080-ffffffff81711092: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff82907cc3)
Location: drivers/usb/core/usb.c:61
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff8174fe00-ffffffff8174fe12: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff82adfae7)
Location: drivers/usb/core/usb.c:61
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff81774230-ffffffff81774242: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff82b04b89)
Location: drivers/usb/core/usb.c:60
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff817b2360-ffffffff817b2372: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff82b13b01)
Location: drivers/usb/core/usb.c:60
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff817e2a90-ffffffff817e2aa2: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff82f255b2)
Location: drivers/usb/core/usb.c:60
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff818b15e0-ffffffff818b15f2: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8321db1f)
Location: drivers/usb/core/usb.c:58
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff818bff90-ffffffff818bffa2: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff83451b03)
Location: drivers/usb/core/usb.c:58
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff818a3160-ffffffff818a3172: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:58
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff81d1362c-ffffffff81d1364c: usb_disabled.cold (STB_LOCAL)
ffffffff81938630-ffffffff81938648: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:58
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff81ede420-ffffffff81ede44a: usb_disabled.cold (STB_LOCAL)
ffffffff81a8ff90-ffffffff81a8ffb2: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff842b1fe0)
Location: drivers/usb/core/usb.c:58
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff8209e692-ffffffff8209e6bc: usb_disabled.cold (STB_LOCAL)
ffffffff81c11e50-ffffffff81c11e72: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff83af4cc0)
Location: drivers/usb/core/usb.c:58
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff8211fc19-ffffffff8211fc43: usb_disabled.cold (STB_LOCAL)
ffffffff81c78c10-ffffffff81c78c32: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff83d50a60)
Location: drivers/usb/core/usb.c:59
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff822013ef-ffffffff82201419: usb_disabled.cold (STB_LOCAL)
ffffffff81d2d610-ffffffff81d2d632: usb_disabled (STB_GLOBAL)
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
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffff8000114ba5c4)
Location: drivers/usb/core/usb.c:60
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-orion.c:ehci_orion_init
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffff800010a10d60-ffff800010a10d80: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c15c0740)
Location: drivers/usb/core/usb.c:60
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-orion.c:ehci_orion_init
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-exynos.c:ehci_exynos_init
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-exynos.c:ohci_exynos_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
c0ae9470-c0ae9494: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c0000000013cde84)
Location: drivers/usb/core/usb.c:60
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
c000000000ac7c10-c000000000ac7c2c: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffe0000a2066)
Location: drivers/usb/core/usb.c:60
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffe000636a28-ffffffe000636a4a: usb_disabled (STB_GLOBAL)
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
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff82af3aa9)
Location: drivers/usb/core/usb.c:60
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff8179ae70-ffffffff8179ae82: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff82ac3f50)
Location: drivers/usb/core/usb.c:60
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff8178cb00-ffffffff8178cb12: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff82b0ee17)
Location: drivers/usb/core/usb.c:60
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff817d7910-ffffffff817d7922: usb_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int usb_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff82b03939)
Location: drivers/usb/core/usb.c:60
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
Direct callers:
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_init
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci.c:xhci_hcd_init
```
**Symbols:**

```
ffffffff817f1bb0-ffffffff817f1bc2: usb_disabled (STB_GLOBAL)
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
