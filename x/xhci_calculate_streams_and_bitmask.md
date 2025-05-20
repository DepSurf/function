# Function: <code>xhci_calculate_streams_and_bitmask</code>

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
In drivers/usb/host/xhci.c (ffffffff81650485)
Location: drivers/usb/host/xhci.c:3061
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff816b0df7)
Location: drivers/usb/host/xhci.c:3040
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff816defa7)
Location: drivers/usb/host/xhci.c:3029
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff816f37ab)
Location: drivers/usb/host/xhci.c:2969
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff8175fa7b)
Location: drivers/usb/host/xhci.c:2985
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff817a0463)
Location: drivers/usb/host/xhci.c:3180
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff817c6723)
Location: drivers/usb/host/xhci.c:3197
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff81805b8b)
Location: drivers/usb/host/xhci.c:3238
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff81836a3b)
Location: drivers/usb/host/xhci.c:3308
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_calculate_streams_and_bitmask(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int *num_streams, u32 *changed_ep_bitmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3312
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff819056c0-ffffffff8190588a: xhci_calculate_streams_and_bitmask (STB_LOCAL)
ffffffff8190b1c1-ffffffff8190b233: xhci_calculate_streams_and_bitmask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_calculate_streams_and_bitmask(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int *num_streams, u32 *changed_ep_bitmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3446
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff8190dec0-ffffffff8190e08a: xhci_calculate_streams_and_bitmask (STB_LOCAL)
ffffffff81c20bee-ffffffff81c20c60: xhci_calculate_streams_and_bitmask.cold (STB_LOCAL)
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
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3373
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff818f13c0-ffffffff818f1585: xhci_calculate_streams_and_bitmask.constprop.0 (STB_LOCAL)
ffffffff81c12c16-ffffffff81c12c88: xhci_calculate_streams_and_bitmask.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3390
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff8198e1d0-ffffffff8198e491: xhci_calculate_streams_and_bitmask.constprop.0 (STB_LOCAL)
ffffffff81d1f970-ffffffff81d1f9ee: xhci_calculate_streams_and_bitmask.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3424
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81aea5f0-ffffffff81aea8d7: xhci_calculate_streams_and_bitmask.constprop.0 (STB_LOCAL)
ffffffff81eeb532-ffffffff81eeb595: xhci_calculate_streams_and_bitmask.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81c76a20)
Location: drivers/usb/host/xhci.c:3422
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81c76a20-ffffffff81c76d68: xhci_calculate_streams_and_bitmask.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81cddb00)
Location: drivers/usb/host/xhci.c:3262
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81cddb00-ffffffff81cdde46: xhci_calculate_streams_and_bitmask.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81d92b10)
Location: drivers/usb/host/xhci.c:3313
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81d92b10-ffffffff81d92e56: xhci_calculate_streams_and_bitmask.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3308
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (c0b483b4)
Location: drivers/usb/host/xhci.c:3308
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (c000000000b4aa08)
Location: drivers/usb/host/xhci.c:3308
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffe00068caac)
Location: drivers/usb/host/xhci.c:3308
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff817eedeb)
Location: drivers/usb/host/xhci.c:3308
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817b3efb)
Location: drivers/usb/host/xhci.c:3308
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8182b8bb)
Location: drivers/usb/host/xhci.c:3308
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff8184588b)
Location: drivers/usb/host/xhci.c:3308
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
