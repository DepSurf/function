# Function: <code>xhci_calculate_lpm_timeout</code>

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
In drivers/usb/host/xhci.c (ffffffff81651552)
Location: drivers/usb/host/xhci.c:4552
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff816b1ead)
Location: drivers/usb/host/xhci.c:4534
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff816e005d)
Location: drivers/usb/host/xhci.c:4527
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff816f2696)
Location: drivers/usb/host/xhci.c:4477
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff8175e976)
Location: drivers/usb/host/xhci.c:4484
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff8179f3cc)
Location: drivers/usb/host/xhci.c:4669
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff817c561e)
Location: drivers/usb/host/xhci.c:4701
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff81804b5e)
Location: drivers/usb/host/xhci.c:4746
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff81835a2e)
Location: drivers/usb/host/xhci.c:4817
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4827
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81904ce0-ffffffff81904f25: xhci_calculate_lpm_timeout (STB_LOCAL)
ffffffff8190b154-ffffffff8190b173: xhci_calculate_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4965
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8190d570-ffffffff8190d7b5: xhci_calculate_lpm_timeout (STB_LOCAL)
ffffffff81c20b81-ffffffff81c20ba0: xhci_calculate_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4892
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff818f0b00-ffffffff818f0d45: xhci_calculate_lpm_timeout (STB_LOCAL)
ffffffff81c12bb6-ffffffff81c12bd5: xhci_calculate_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4912
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8198df70-ffffffff8198e1d0: xhci_calculate_lpm_timeout (STB_LOCAL)
ffffffff81d1f951-ffffffff81d1f970: xhci_calculate_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u16 xhci_calculate_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4936
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81aea3f0-ffffffff81aea5f0: xhci_calculate_lpm_timeout (STB_LOCAL)
ffffffff81eeb510-ffffffff81eeb532: xhci_calculate_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 xhci_calculate_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c76790)
Location: drivers/usb/host/xhci.c:4940
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81c76790-ffffffff81c769a6: xhci_calculate_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 xhci_calculate_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdd880)
Location: drivers/usb/host/xhci.c:4774
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81cdd880-ffffffff81cdda89: xhci_calculate_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 xhci_calculate_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d92890)
Location: drivers/usb/host/xhci.c:4834
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81d92890-ffffffff81d92a99: xhci_calculate_lpm_timeout (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffff800010a73654)
Location: drivers/usb/host/xhci.c:4817
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (c0b4728c)
Location: drivers/usb/host/xhci.c:4817
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (c000000000b49294)
Location: drivers/usb/host/xhci.c:4817
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffe00068ba62)
Location: drivers/usb/host/xhci.c:4817
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff817eddde)
Location: drivers/usb/host/xhci.c:4817
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff817b2eee)
Location: drivers/usb/host/xhci.c:4817
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff8182a8ae)
Location: drivers/usb/host/xhci.c:4817
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff8184487e)
Location: drivers/usb/host/xhci.c:4817
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
