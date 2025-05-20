# Function: <code>usb_hcd_poll_rh_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8160cff0)
Location: drivers/usb/core/hcd.c:756
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8160cff0-ffffffff8160d14f: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8166cb60)
Location: drivers/usb/core/hcd.c:755
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8166cb60-ffffffff8166ccc1: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8169a860)
Location: drivers/usb/core/hcd.c:756
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8169a860-ffffffff8169a9c1: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff816afad0)
Location: drivers/usb/core/hcd.c:760
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff816afad0-ffffffff816afc86: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8171b140)
Location: drivers/usb/core/hcd.c:747
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8171b140-ffffffff8171b2fc: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:749
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
ffffffff8175cd87-ffffffff8175cd93: usb_hcd_poll_rh_status.cold.38 (STB_LOCAL)
ffffffff81759f10-ffffffff8175a0af: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:749
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
ffffffff81781347-ffffffff81781353: usb_hcd_poll_rh_status.cold.41 (STB_LOCAL)
ffffffff8177e490-ffffffff8177e62f: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
ffffffff817bf0c2-ffffffff817bf0ce: usb_hcd_poll_rh_status.cold (STB_LOCAL)
ffffffff817bca10-ffffffff817bcbaf: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
ffffffff817efa42-ffffffff817efa4e: usb_hcd_poll_rh_status.cold (STB_LOCAL)
ffffffff817ed230-ffffffff817ed3cf: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:753
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff818bf3bc-ffffffff818bf3c8: usb_hcd_poll_rh_status.cold (STB_LOCAL)
ffffffff818bd260-ffffffff818bd427: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff81c1c9e9-ffffffff81c1c9f5: usb_hcd_poll_rh_status.cold (STB_LOCAL)
ffffffff818c9e50-ffffffff818ca017: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff81c0e7c5-ffffffff81c0e7d1: usb_hcd_poll_rh_status.cold (STB_LOCAL)
ffffffff818ad190-ffffffff818ad357: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff81d1595e-ffffffff81d1596a: usb_hcd_poll_rh_status.cold (STB_LOCAL)
ffffffff81942230-ffffffff81942426: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff81ee0477-ffffffff81ee0483: usb_hcd_poll_rh_status.cold (STB_LOCAL)
ffffffff81a9ac00-ffffffff81a9ae0b: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1f410)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff81c1f410-ffffffff81c1f627: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c86380)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff81c86380-ffffffff81c86597: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d3ae20)
Location: drivers/usb/core/hcd.c:727
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
ffffffff81d3ae20-ffffffff81d3b02d: usb_hcd_poll_rh_status (STB_GLOBAL)
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
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1d700)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
ffff800010a1d700-ffff800010a1d990: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af4140)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/musb/musb_virthub.c:musb_root_disconnect
  - drivers/usb/musb/musb_virthub.c:musb_port_reset
  - drivers/usb/musb/musb_virthub.c:musb_host_finish_resume
  - drivers/usb/musb/musb_host.c:musb_host_poke_root_hub
```
**Symbols:**

```
c0af4140-c0af42e0: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad6150)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
c000000000ad6150-c000000000ad63d0: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe000640a0e)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
ffffffe000640a0e-ffffffe000640b52: usb_hcd_poll_rh_status (STB_GLOBAL)
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
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
ffffffff817a7e22-ffffffff817a7e2e: usb_hcd_poll_rh_status.cold (STB_LOCAL)
ffffffff817a5610-ffffffff817a57af: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
ffffffff8179983b-ffffffff81799847: usb_hcd_poll_rh_status.cold (STB_LOCAL)
ffffffff817970d0-ffffffff8179726f: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
ffffffff817e48c2-ffffffff817e48ce: usb_hcd_poll_rh_status.cold (STB_LOCAL)
ffffffff817e20b0-ffffffff817e224f: usb_hcd_poll_rh_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void usb_hcd_poll_rh_status(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:752
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_timer_func
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:compliance_mode_recovery
```
**Symbols:**

```
ffffffff817feb2e-ffffffff817feb3a: usb_hcd_poll_rh_status.cold (STB_LOCAL)
ffffffff817fc4e0-ffffffff817fc679: usb_hcd_poll_rh_status (STB_GLOBAL)
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
