# Function: <code>usb_put_hcd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8160cb70)
Location: drivers/usb/core/hcd.c:2627
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8160cb70-ffffffff8160cb9b: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8166c6f0)
Location: drivers/usb/core/hcd.c:2631
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8166c6f0-ffffffff8166c71b: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8169a3f0)
Location: drivers/usb/core/hcd.c:2630
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8169a3f0-ffffffff8169a41b: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff816af3c0)
Location: drivers/usb/core/hcd.c:2656
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff816af3c0-ffffffff816af43c: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8171ac40)
Location: drivers/usb/core/hcd.c:2643
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8171ac40-ffffffff8171ac70: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81759980)
Location: drivers/usb/core/hcd.c:2659
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff81759980-ffffffff817599b1: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8177def0)
Location: drivers/usb/core/hcd.c:2643
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8177def0-ffffffff8177df21: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817bc430)
Location: drivers/usb/core/hcd.c:2554
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817bc430-ffffffff817bc45f: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817ecc50)
Location: drivers/usb/core/hcd.c:2553
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817ecc50-ffffffff817ecc7f: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bc010)
Location: drivers/usb/core/hcd.c:2550
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff818bc010-ffffffff818bc057: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818c8dd0)
Location: drivers/usb/core/hcd.c:2562
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff818c8dd0-ffffffff818c8e17: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818ac380)
Location: drivers/usb/core/hcd.c:2562
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff818ac380-ffffffff818ac3c7: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff819413d0)
Location: drivers/usb/core/hcd.c:2713
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff819413d0-ffffffff81941417: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81a99b70)
Location: drivers/usb/core/hcd.c:2716
Inline: True
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81a99b70-ffffffff81a99be7: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1dd10)
Location: drivers/usb/core/hcd.c:2710
Inline: True
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81c1dd10-ffffffff81c1dd87: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c84c10)
Location: drivers/usb/core/hcd.c:2714
Inline: True
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81c84c10-ffffffff81c84c87: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d39610)
Location: drivers/usb/core/hcd.c:2689
Inline: True
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81d39610-ffffffff81d39687: usb_put_hcd (STB_GLOBAL)
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
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1bad0)
Location: drivers/usb/core/hcd.c:2553
Inline: True
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_remove
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffff800010a1bad0-ffff800010a1bb58: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af3a80)
Location: drivers/usb/core/hcd.c:2553
Inline: True
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_remove
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_remove
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_remove
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_remove
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_remove
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_remove
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/musb/musb_host.c:musb_host_free
```
**Symbols:**

```
c0af3a80-c0af3afc: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad5120)
Location: drivers/usb/core/hcd.c:2553
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_remove
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
c000000000ad5120-c000000000ad520c: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe00063fd74)
Location: drivers/usb/core/hcd.c:2553
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffe00063fd74-ffffffe00063fe04: usb_put_hcd (STB_GLOBAL)
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
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817a5030)
Location: drivers/usb/core/hcd.c:2553
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817a5030-ffffffff817a505f: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81796b40)
Location: drivers/usb/core/hcd.c:2553
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff81796b40-ffffffff81796b6f: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817e1ad0)
Location: drivers/usb/core/hcd.c:2553
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817e1ad0-ffffffff817e1aff: usb_put_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void usb_put_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817fbec0)
Location: drivers/usb/core/hcd.c:2553
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_release_dev
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817fbec0-ffffffff817fbeef: usb_put_hcd (STB_GLOBAL)
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
