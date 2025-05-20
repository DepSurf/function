# Function: <code>uhci_submit_isochronous</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81648f0c)
Location: drivers/usb/host/uhci-q.c:1255
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a99c2)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d7b07)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816ebd65)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81758555)
Location: drivers/usb/host/uhci-q.c:1255
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81797ce6)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817be226)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817fd0d6)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8182df26)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uhci_submit_isochronous(struct uhci_hcd *uhci, struct urb *urb, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81900180)
Location: drivers/usb/host/uhci-q.c:1254
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81900180-ffffffff81900581: uhci_submit_isochronous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uhci_submit_isochronous(struct uhci_hcd *uhci, struct urb *urb, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81908a50)
Location: drivers/usb/host/uhci-q.c:1254
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81908a50-ffffffff81908e51: uhci_submit_isochronous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818ec0e0)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff818ec0e0-ffffffff818ec4de: uhci_submit_isochronous.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff819887f0)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff819887f0-ffffffff81988beb: uhci_submit_isochronous.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae6440)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81ae6440-ffffffff81ae6848: uhci_submit_isochronous.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c721f0)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81c721f0-ffffffff81c725f8: uhci_submit_isochronous.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd97e0)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81cd97e0-ffffffff81cd9be8: uhci_submit_isochronous.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8e7f0)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81d8e7f0-ffffffff81d8ebf8: uhci_submit_isochronous.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a6bc90)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b3c7f4)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b3b9e8)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe000683eea)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817e6306)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81822da6)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8183e4c6)
Location: drivers/usb/host/uhci-q.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
