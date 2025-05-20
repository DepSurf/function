# Function: <code>usb_hcd_giveback_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8160cf00)
Location: drivers/usb/core/hcd.c:1824
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff8160cf00-ffffffff8160cfe3: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8166ca80)
Location: drivers/usb/core/hcd.c:1820
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff8166ca80-ffffffff8166cb5e: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8169a780)
Location: drivers/usb/core/hcd.c:1821
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff8169a780-ffffffff8169a85e: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff816af9f0)
Location: drivers/usb/core/hcd.c:1835
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff816af9f0-ffffffff816afac9: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8171b060)
Location: drivers/usb/core/hcd.c:1824
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff8171b060-ffffffff8171b139: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81759e30)
Location: drivers/usb/core/hcd.c:1826
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81759e30-ffffffff81759f0a: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8177e3b0)
Location: drivers/usb/core/hcd.c:1810
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff8177e3b0-ffffffff8177e48a: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817bc930)
Location: drivers/usb/core/hcd.c:1712
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff817bc930-ffffffff817bca0a: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817ed150)
Location: drivers/usb/core/hcd.c:1709
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff817ed150-ffffffff817ed22a: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bc970)
Location: drivers/usb/core/hcd.c:1706
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff818bc970-ffffffff818bca4a: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818c9680)
Location: drivers/usb/core/hcd.c:1716
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff818c9680-ffffffff818c975a: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818acfb0)
Location: drivers/usb/core/hcd.c:1716
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff818acfb0-ffffffff818ad08a: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:1737
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81d15949-ffffffff81d1595e: usb_hcd_giveback_urb.cold (STB_LOCAL)
ffffffff81942040-ffffffff81942127: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:1743
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81ee0438-ffffffff81ee0462: usb_hcd_giveback_urb.cold (STB_LOCAL)
ffffffff81a99f00-ffffffff81a9a005: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:1744
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff8209e86a-ffffffff8209e894: usb_hcd_giveback_urb.cold (STB_LOCAL)
ffffffff81c1e460-ffffffff81c1e565: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:1748
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff8211fe02-ffffffff8211fe2a: usb_hcd_giveback_urb.cold (STB_LOCAL)
ffffffff81c85350-ffffffff81c8546b: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:1723
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff822015d8-ffffffff82201600: usb_hcd_giveback_urb.cold (STB_LOCAL)
ffffffff81d39d50-ffffffff81d39e6b: usb_hcd_giveback_urb (STB_GLOBAL)
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
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1cb78)
Location: drivers/usb/core/hcd.c:1709
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffff800010a1cb78-ffff800010a1cd08: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af404c)
Location: drivers/usb/core/hcd.c:1709
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_giveback_urb_in_irq
  - drivers/usb/musb/musb_host.c:musb_giveback
```
**Symbols:**

```
c0af404c-c0af4140: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad5fc0)
Location: drivers/usb/core/hcd.c:1709
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
c000000000ad5fc0-c000000000ad6150: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe0006408f6)
Location: drivers/usb/core/hcd.c:1709
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffe0006408f6-ffffffe000640a0e: usb_hcd_giveback_urb (STB_GLOBAL)
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
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817a5530)
Location: drivers/usb/core/hcd.c:1709
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff817a5530-ffffffff817a560a: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81796ff0)
Location: drivers/usb/core/hcd.c:1709
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81796ff0-ffffffff817970ca: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817e1fd0)
Location: drivers/usb/core/hcd.c:1709
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff817e1fd0-ffffffff817e20aa: usb_hcd_giveback_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void usb_hcd_giveback_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817fc3b0)
Location: drivers/usb/core/hcd.c:1709
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff817fc3b0-ffffffff817fc4d8: usb_hcd_giveback_urb (STB_GLOBAL)
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
