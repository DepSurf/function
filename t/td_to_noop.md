# Function: <code>td_to_noop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void td_to_noop(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, struct xhci_td *cur_td, bool flip_cycle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81657810)
Location: drivers/usb/host/xhci-ring.c:531
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81657810-ffffffff816579a7: td_to_noop (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff816b8120)
Location: drivers/usb/host/xhci-ring.c:513
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816b8120-ffffffff816b8282: td_to_noop.constprop.53 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff816e6400)
Location: drivers/usb/host/xhci-ring.c:596
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816e6400-ffffffff816e6484: td_to_noop.constprop.60 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff816fa170)
Location: drivers/usb/host/xhci-ring.c:610
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816fa170-ffffffff816fa1f4: td_to_noop.constprop.67 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81766bb0)
Location: drivers/usb/host/xhci-ring.c:599
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81766bb0-ffffffff81766c34: td_to_noop.constprop.63 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff817a77e0)
Location: drivers/usb/host/xhci-ring.c:599
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817a77e0-ffffffff817a7864: td_to_noop.constprop.61 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff817cd690)
Location: drivers/usb/host/xhci-ring.c:599
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817cd690-ffffffff817cd714: td_to_noop.constprop.64 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff8180d710)
Location: drivers/usb/host/xhci-ring.c:606
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff8180d710-ffffffff8180d794: td_to_noop.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff8183e800)
Location: drivers/usb/host/xhci-ring.c:606
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff8183e800-ffffffff8183e884: td_to_noop.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81910de0)
Location: drivers/usb/host/xhci-ring.c:630
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff81910de0-ffffffff81910e64: td_to_noop.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81918720)
Location: drivers/usb/host/xhci-ring.c:630
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff81918720-ffffffff8191879e: td_to_noop.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff818fba30)
Location: drivers/usb/host/xhci-ring.c:687
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff818fba30-ffffffff818fbab1: td_to_noop.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff8199a8b0)
Location: drivers/usb/host/xhci-ring.c:723
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff8199a8b0-ffffffff8199a931: td_to_noop.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81af79e0)
Location: drivers/usb/host/xhci-ring.c:723
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff81af79e0-ffffffff81af7a72: td_to_noop.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81c856e0)
Location: drivers/usb/host/xhci-ring.c:723
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff81c856e0-ffffffff81c85772: td_to_noop.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81cec530)
Location: drivers/usb/host/xhci-ring.c:754
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff81cec530-ffffffff81cec5c2: td_to_noop.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81da1b60)
Location: drivers/usb/host/xhci-ring.c:762
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff81da1b60-ffffffff81da1c06: td_to_noop.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffff800010a7c360)
Location: drivers/usb/host/xhci-ring.c:606
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffff800010a7c360-ffff800010a7c428: td_to_noop.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (c0b5047c)
Location: drivers/usb/host/xhci-ring.c:606
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
c0b5047c-c0b5051c: td_to_noop.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (c000000000b54e30)
Location: drivers/usb/host/xhci-ring.c:606
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
c000000000b54e30-c000000000b54ee8: td_to_noop.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffe000693dd8)
Location: drivers/usb/host/xhci-ring.c:606
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffe000693dd8-ffffffe000693e72: td_to_noop.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff817f6bb0)
Location: drivers/usb/host/xhci-ring.c:606
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff817f6bb0-ffffffff817f6c34: td_to_noop.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817bbd50)
Location: drivers/usb/host/xhci-ring.c:606
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff817bbd50-ffffffff817bbdd4: td_to_noop.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81833680)
Location: drivers/usb/host/xhci-ring.c:606
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff81833680-ffffffff81833704: td_to_noop.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff8184da40)
Location: drivers/usb/host/xhci-ring.c:606
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
```
**Symbols:**

```
ffffffff8184da40-ffffffff8184dac4: td_to_noop.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
