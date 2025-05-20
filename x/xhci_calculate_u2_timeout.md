# Function: <code>xhci_calculate_u2_timeout</code>

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
In drivers/usb/host/xhci.c (ffffffff8164b730)
Location: drivers/usb/host/xhci.c:4434
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8164b730-ffffffff8164b7fa: xhci_calculate_u2_timeout.isra.36 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff816ac120)
Location: drivers/usb/host/xhci.c:4416
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff816ac120-ffffffff816ac1fd: xhci_calculate_u2_timeout.isra.38 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff816da250)
Location: drivers/usb/host/xhci.c:4409
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff816da250-ffffffff816da32d: xhci_calculate_u2_timeout.isra.40 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff816ee3c1)
Location: drivers/usb/host/xhci.c:4359
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
In drivers/usb/host/xhci.c (ffffffff8175ac01)
Location: drivers/usb/host/xhci.c:4366
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
In drivers/usb/host/xhci.c (ffffffff8179b379)
Location: drivers/usb/host/xhci.c:4551
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
In drivers/usb/host/xhci.c (ffffffff817c19a0)
Location: drivers/usb/host/xhci.c:4575
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817c19a0-ffffffff817c1ab2: xhci_calculate_u2_timeout.isra.46 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff818013e0)
Location: drivers/usb/host/xhci.c:4620
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff818013e0-ffffffff818014f9: xhci_calculate_u2_timeout.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81832490)
Location: drivers/usb/host/xhci.c:4691
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81832490-ffffffff818325a9: xhci_calculate_u2_timeout.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u16 xhci_calculate_u2_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81904550)
Location: drivers/usb/host/xhci.c:4701
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff81904550-ffffffff8190466a: xhci_calculate_u2_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u16 xhci_calculate_u2_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190cdd0)
Location: drivers/usb/host/xhci.c:4839
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff8190cdd0-ffffffff8190cef2: xhci_calculate_u2_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u16 xhci_calculate_u2_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f0370)
Location: drivers/usb/host/xhci.c:4766
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff818f0370-ffffffff818f048f: xhci_calculate_u2_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_u2_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4787
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff8198dc70-ffffffff8198ddc8: xhci_calculate_u2_timeout (STB_LOCAL)
ffffffff81d1f8a0-ffffffff81d1f913: xhci_calculate_u2_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_u2_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4814
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff81aea0e0-ffffffff81aea245: xhci_calculate_u2_timeout (STB_LOCAL)
ffffffff81eeb45d-ffffffff81eeb4d2: xhci_calculate_u2_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_u2_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4818
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff81c76450-ffffffff81c765b5: xhci_calculate_u2_timeout (STB_LOCAL)
ffffffff820a569e-ffffffff820a5713: xhci_calculate_u2_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_u2_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4659
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff81cdd560-ffffffff81cdd69a: xhci_calculate_u2_timeout (STB_LOCAL)
ffffffff82126b97-ffffffff82126bb0: xhci_calculate_u2_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_u2_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4719
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
```
**Symbols:**

```
ffffffff81d92570-ffffffff81d926aa: xhci_calculate_u2_timeout (STB_LOCAL)
ffffffff8220839a-ffffffff822083b3: xhci_calculate_u2_timeout.cold (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffff800010a6e848)
Location: drivers/usb/host/xhci.c:4691
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffff800010a6e848-ffff800010a6e99c: xhci_calculate_u2_timeout.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u16 xhci_calculate_u2_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b44070)
Location: drivers/usb/host/xhci.c:4691
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
c0b44070-c0b44298: xhci_calculate_u2_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u16 xhci_calculate_u2_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b420a0)
Location: drivers/usb/host/xhci.c:4691
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
c000000000b420a0-c000000000b42264: xhci_calculate_u2_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u16 xhci_calculate_u2_timeout(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe0006871b0)
Location: drivers/usb/host/xhci.c:4691
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffe0006871b0-ffffffe0006872f8: xhci_calculate_u2_timeout (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff817ea870)
Location: drivers/usb/host/xhci.c:4691
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817ea870-ffffffff817ea989: xhci_calculate_u2_timeout.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff817af980)
Location: drivers/usb/host/xhci.c:4691
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817af980-ffffffff817afa99: xhci_calculate_u2_timeout.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81827310)
Location: drivers/usb/host/xhci.c:4691
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81827310-ffffffff81827429: xhci_calculate_u2_timeout.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff818412b0)
Location: drivers/usb/host/xhci.c:4691
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff818412b0-ffffffff818413c9: xhci_calculate_u2_timeout.isra.0 (STB_LOCAL)
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
