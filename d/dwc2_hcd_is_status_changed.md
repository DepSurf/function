# Function: <code>dwc2_hcd_is_status_changed</code>

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
In drivers/usb/dwc2/hcd.c (ffffffff81627ef5)
Location: drivers/usb/dwc2/hcd.c:1848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff81686b95)
Location: drivers/usb/dwc2/hcd.c:3705
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff816b4dc5)
Location: drivers/usb/dwc2/hcd.c:3736
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff816c90f5)
Location: drivers/usb/dwc2/hcd.c:3764
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff81735605)
Location: drivers/usb/dwc2/hcd.c:3773
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff81774898)
Location: drivers/usb/dwc2/hcd.c:3903
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff817999d8)
Location: drivers/usb/dwc2/hcd.c:3903
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff817d8dd8)
Location: drivers/usb/dwc2/hcd.c:3723
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff81809c68)
Location: drivers/usb/dwc2/hcd.c:3723
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff818da590)
Location: drivers/usb/dwc2/hcd.c:3723
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
```
**Symbols:**

```
ffffffff818da590-ffffffff818da6b2: dwc2_hcd_is_status_changed.constprop.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff818e44b0)
Location: drivers/usb/dwc2/hcd.c:3724
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
```
**Symbols:**

```
ffffffff818e44b0-ffffffff818e45d2: dwc2_hcd_is_status_changed.constprop.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff818c7370)
Location: drivers/usb/dwc2/hcd.c:3775
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
```
**Symbols:**

```
ffffffff818c7370-ffffffff818c7492: dwc2_hcd_is_status_changed.constprop.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff8195ec40)
Location: drivers/usb/dwc2/hcd.c:3775
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
```
**Symbols:**

```
ffffffff8195ec40-ffffffff8195ed56: dwc2_hcd_is_status_changed.constprop.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff81ab9070)
Location: drivers/usb/dwc2/hcd.c:3771
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
```
**Symbols:**

```
ffffffff81ab9070-ffffffff81ab91a4: dwc2_hcd_is_status_changed.constprop.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff81c422b0)
Location: drivers/usb/dwc2/hcd.c:3742
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
```
**Symbols:**

```
ffffffff81c422b0-ffffffff81c423e4: dwc2_hcd_is_status_changed.constprop.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff81ca9880)
Location: drivers/usb/dwc2/hcd.c:3742
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
```
**Symbols:**

```
ffffffff81ca9880-ffffffff81ca99b4: dwc2_hcd_is_status_changed.constprop.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff81d5e530)
Location: drivers/usb/dwc2/hcd.c:3742
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
```
**Symbols:**

```
ffffffff81d5e530-ffffffff81d5e664: dwc2_hcd_is_status_changed.constprop.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffff800010a403b8)
Location: drivers/usb/dwc2/hcd.c:3723
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (c0b12f68)
Location: drivers/usb/dwc2/hcd.c:3723
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (c000000000b01198)
Location: drivers/usb/dwc2/hcd.c:3723
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffe00065c42a)
Location: drivers/usb/dwc2/hcd.c:3723
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff817c2048)
Location: drivers/usb/dwc2/hcd.c:3723
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff817feae8)
Location: drivers/usb/dwc2/hcd.c:3723
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
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
In drivers/usb/dwc2/hcd.c (ffffffff81818bf8)
Location: drivers/usb/dwc2/hcd.c:3723
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_status_data
```
</details>
</li>
</ul>

## Differences
