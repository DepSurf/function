# Function: <code>uhci_get_current_frame_number</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81645af0)
Location: drivers/usb/host/uhci-hcd.c:504
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81645af0-ffffffff81645b18: uhci_get_current_frame_number.part.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a8dc3)
Location: drivers/usb/host/uhci-hcd.c:504
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff816a6620-ffffffff816a6648: uhci_get_current_frame_number.part.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d6ee3)
Location: drivers/usb/host/uhci-hcd.c:504
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff816d4740-ffffffff816d4768: uhci_get_current_frame_number.part.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816eb187)
Location: drivers/usb/host/uhci-hcd.c:515
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff816e8bd0-ffffffff816e8bf8: uhci_get_current_frame_number.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81757977)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff817553b0-ffffffff817553d8: uhci_get_current_frame_number.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81799987)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff817959a0-ffffffff817959c8: uhci_get_current_frame_number.part.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817bf607)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff817bc0c0-ffffffff817bc0e8: uhci_get_current_frame_number.part.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817fef37)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff817fb2a0-ffffffff817fb2c8: uhci_get_current_frame_number.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8182fd97)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff8182c0e0-ffffffff8182c108: uhci_get_current_frame_number.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818ff8c0)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81908190)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818eb780)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81987e90)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae4b90)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c70770)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd7d60)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8cd70)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a6c49c)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffff800010a67a18-ffff800010a67a5c: uhci_get_current_frame_number.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b3eb18)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
c0b3b2e0-c0b3b364: uhci_get_current_frame_number.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b3e968)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
c000000000b3a340-c000000000b3a46c: uhci_get_current_frame_number.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe000686076)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffe0006823a8-ffffffe0006823f4: uhci_get_current_frame_number.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817e8177)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff817e44c0-ffffffff817e44e8: uhci_get_current_frame_number.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81824c17)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff81820f60-ffffffff81820f88: uhci_get_current_frame_number.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8183d947)
Location: drivers/usb/host/uhci-hcd.c:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
Direct callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
**Symbols:**

```
ffffffff8183b3c0-ffffffff8183b3e8: uhci_get_current_frame_number.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
