# Function: <code>usb_hcd_check_unlink_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8160c040)
Location: drivers/usb/core/hcd.c:1312
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff8160c040-ffffffff8160c08c: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8166cd31)
Location: drivers/usb/core/hcd.c:1304
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff8166bbf0-ffffffff8166bc3c: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8169aa31)
Location: drivers/usb/core/hcd.c:1305
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff816998f0-ffffffff8169993c: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff816afcf1)
Location: drivers/usb/core/hcd.c:1308
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff816aec20-ffffffff816aec6c: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8171b377)
Location: drivers/usb/core/hcd.c:1297
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff8171a210-ffffffff8171a25c: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8175a135)
Location: drivers/usb/core/hcd.c:1299
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81759030-ffffffff8175907c: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8177e6b5)
Location: drivers/usb/core/hcd.c:1297
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff8177d5a0-ffffffff8177d5ec: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817bcc30)
Location: drivers/usb/core/hcd.c:1202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff817bb9f0-ffffffff817bba3c: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817ed450)
Location: drivers/usb/core/hcd.c:1202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff817ec220-ffffffff817ec26c: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bcab0)
Location: drivers/usb/core/hcd.c:1203
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff818bb830-ffffffff818bb87e: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818c97c0)
Location: drivers/usb/core/hcd.c:1204
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff818c8610-ffffffff818c865e: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818adf32)
Location: drivers/usb/core/hcd.c:1204
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff818abc60-ffffffff818abcac: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81943002)
Location: drivers/usb/core/hcd.c:1211
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81940c50-ffffffff81940c9c: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81a9af95)
Location: drivers/usb/core/hcd.c:1211
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81a98e80-ffffffff81a98ef0: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1fdd5)
Location: drivers/usb/core/hcd.c:1211
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81c1cdc0-ffffffff81c1ce30: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c86d47)
Location: drivers/usb/core/hcd.c:1215
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81c83cd0-ffffffff81c83d40: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d3b7a7)
Location: drivers/usb/core/hcd.c:1190
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81d386d0-ffffffff81d38740: usb_hcd_check_unlink_urb (STB_GLOBAL)
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
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1e210)
Location: drivers/usb/core/hcd.c:1202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffff800010a1b250-ffff800010a1b2c8: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af4b3c)
Location: drivers/usb/core/hcd.c:1202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/musb/musb_host.c:musb_urb_dequeue
```
**Symbols:**

```
c0af3190-c0af31fc: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad6498)
Location: drivers/usb/core/hcd.c:1202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
c000000000ad47e0-c000000000ad4850: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe000641328)
Location: drivers/usb/core/hcd.c:1202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffe00063f864-ffffffe00063f8b8: usb_hcd_check_unlink_urb (STB_GLOBAL)
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
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817a5830)
Location: drivers/usb/core/hcd.c:1202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff817a4600-ffffffff817a464c: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817972f0)
Location: drivers/usb/core/hcd.c:1202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81796170-ffffffff817961bc: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817e22d0)
Location: drivers/usb/core/hcd.c:1202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff817e10a0-ffffffff817e10ec: usb_hcd_check_unlink_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_check_unlink_urb(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817fd120)
Location: drivers/usb/core/hcd.c:1202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:unlink1
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff817fb390-ffffffff817fb3dc: usb_hcd_check_unlink_urb (STB_GLOBAL)
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
