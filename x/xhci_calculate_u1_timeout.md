# Function: <code>xhci_calculate_u1_timeout</code>

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
In drivers/usb/host/xhci.c (ffffffff8164b600)
Location: drivers/usb/host/xhci.c:4378
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8164b600-ffffffff8164b721: xhci_calculate_u1_timeout.isra.35 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff816ac000)
Location: drivers/usb/host/xhci.c:4360
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff816ac000-ffffffff816ac11e: xhci_calculate_u1_timeout.isra.37 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff816da130)
Location: drivers/usb/host/xhci.c:4353
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff816da130-ffffffff816da24e: xhci_calculate_u1_timeout.isra.39 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff816ee488)
Location: drivers/usb/host/xhci.c:4303
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_update_timeout_for_endpoint
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
In drivers/usb/host/xhci.c (ffffffff8175acc8)
Location: drivers/usb/host/xhci.c:4310
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_update_timeout_for_endpoint
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
In drivers/usb/host/xhci.c (ffffffff8179b33d)
Location: drivers/usb/host/xhci.c:4495
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_update_timeout_for_endpoint
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
In drivers/usb/host/xhci.c (ffffffff817c1830)
Location: drivers/usb/host/xhci.c:4511
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817c1830-ffffffff817c199d: xhci_calculate_u1_timeout.isra.45 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81801280)
Location: drivers/usb/host/xhci.c:4556
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81801280-ffffffff818013d2: xhci_calculate_u1_timeout.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81832330)
Location: drivers/usb/host/xhci.c:4627
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81832330-ffffffff81832482: xhci_calculate_u1_timeout.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u16 xhci_calculate_u1_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81904670)
Location: drivers/usb/host/xhci.c:4637
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff81904670-ffffffff819047d9: xhci_calculate_u1_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u16 xhci_calculate_u1_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190cf00)
Location: drivers/usb/host/xhci.c:4775
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff8190cf00-ffffffff8190d06c: xhci_calculate_u1_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u16 xhci_calculate_u1_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f0490)
Location: drivers/usb/host/xhci.c:4702
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff818f0490-ffffffff818f05f6: xhci_calculate_u1_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_u1_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4723
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff8198ddd0-ffffffff8198df69: xhci_calculate_u1_timeout (STB_LOCAL)
ffffffff81d1f913-ffffffff81d1f951: xhci_calculate_u1_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_u1_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4750
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff81aea250-ffffffff81aea3ea: xhci_calculate_u1_timeout (STB_LOCAL)
ffffffff81eeb4d2-ffffffff81eeb510: xhci_calculate_u1_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_u1_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4754
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff81c765d0-ffffffff81c76777: xhci_calculate_u1_timeout (STB_LOCAL)
ffffffff820a5713-ffffffff820a5751: xhci_calculate_u1_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_u1_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4595
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff81cdd6b0-ffffffff81cdd867: xhci_calculate_u1_timeout (STB_LOCAL)
ffffffff82126bb0-ffffffff82126bc9: xhci_calculate_u1_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_u1_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4655
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff81d926c0-ffffffff81d92877: xhci_calculate_u1_timeout (STB_LOCAL)
ffffffff822083b3-ffffffff822083cc: xhci_calculate_u1_timeout.cold (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffff800010a6e6b0)
Location: drivers/usb/host/xhci.c:4627
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffff800010a6e6b0-ffff800010a6e848: xhci_calculate_u1_timeout.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u16 xhci_calculate_u1_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b44298)
Location: drivers/usb/host/xhci.c:4627
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
c0b44298-c0b44568: xhci_calculate_u1_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u16 xhci_calculate_u1_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b41ea0)
Location: drivers/usb/host/xhci.c:4627
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
c000000000b41ea0-c000000000b420a0: xhci_calculate_u1_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u16 xhci_calculate_u1_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000687044)
Location: drivers/usb/host/xhci.c:4627
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffe000687044-ffffffe0006871b0: xhci_calculate_u1_timeout (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff817ea710)
Location: drivers/usb/host/xhci.c:4627
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817ea710-ffffffff817ea862: xhci_calculate_u1_timeout.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff817af820)
Location: drivers/usb/host/xhci.c:4627
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817af820-ffffffff817af972: xhci_calculate_u1_timeout.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff818271b0)
Location: drivers/usb/host/xhci.c:4627
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff818271b0-ffffffff81827302: xhci_calculate_u1_timeout.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81841150)
Location: drivers/usb/host/xhci.c:4627
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81841150-ffffffff818412a2: xhci_calculate_u1_timeout.isra.0 (STB_LOCAL)
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
</ul>
