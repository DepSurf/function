# Function: <code>xhci_update_timeout_for_endpoint</code>

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
In drivers/usb/host/xhci.c (ffffffff8165157d)
Location: drivers/usb/host/xhci.c:4471
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff816b1ed4)
Location: drivers/usb/host/xhci.c:4453
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff816e0084)
Location: drivers/usb/host/xhci.c:4446
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_update_timeout_for_endpoint(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc, enum usb3_link_state state, u16 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ee390)
Location: drivers/usb/host/xhci.c:4396
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff816ee390-ffffffff816ee5d0: xhci_update_timeout_for_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_update_timeout_for_endpoint(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc, enum usb3_link_state state, u16 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175abd0)
Location: drivers/usb/host/xhci.c:4403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8175abd0-ffffffff8175ae10: xhci_update_timeout_for_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_update_timeout_for_endpoint(struct xhci_hcd *xhci, struct usb_device *udev, struct usb_endpoint_descriptor *desc, enum usb3_link_state state, u16 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179b310)
Location: drivers/usb/host/xhci.c:4588
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8179b310-ffffffff8179b583: xhci_update_timeout_for_endpoint (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff817c5848)
Location: drivers/usb/host/xhci.c:4620
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff81804d5e)
Location: drivers/usb/host/xhci.c:4665
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff81835c5c)
Location: drivers/usb/host/xhci.c:4736
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff81904de8)
Location: drivers/usb/host/xhci.c:4746
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff8190d678)
Location: drivers/usb/host/xhci.c:4884
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff818f0c08)
Location: drivers/usb/host/xhci.c:4811
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff8198e085)
Location: drivers/usb/host/xhci.c:4832
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff81aea507)
Location: drivers/usb/host/xhci.c:4859
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff81c768a1)
Location: drivers/usb/host/xhci.c:4863
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff81cdd9ca)
Location: drivers/usb/host/xhci.c:4704
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff81d929da)
Location: drivers/usb/host/xhci.c:4764
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
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
In drivers/usb/host/xhci.c (ffff800010a73878)
Location: drivers/usb/host/xhci.c:4736
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (c0b474e8)
Location: drivers/usb/host/xhci.c:4736
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (c000000000b495b0)
Location: drivers/usb/host/xhci.c:4736
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffe00068ba80)
Location: drivers/usb/host/xhci.c:4736
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff817ee00c)
Location: drivers/usb/host/xhci.c:4736
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff817b311c)
Location: drivers/usb/host/xhci.c:4736
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff8182aadc)
Location: drivers/usb/host/xhci.c:4736
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
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
In drivers/usb/host/xhci.c (ffffffff81844aac)
Location: drivers/usb/host/xhci.c:4736
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
