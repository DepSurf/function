# Function: <code>dwc2_hcd_hub_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dwc2_hcd_hub_control(struct dwc2_hsotg *hsotg, u16 typereq, u16 wvalue, u16 windex, char *buf, u16 wlength);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816270a0)
Location: drivers/usb/dwc2/hcd.c:1536
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff816270a0-ffffffff816279f9: dwc2_hcd_hub_control (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff81686cc0)
Location: drivers/usb/dwc2/hcd.c:3371
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff81686cc0-ffffffff816875a1: dwc2_hcd_hub_control.constprop.43 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff816b4ef0)
Location: drivers/usb/dwc2/hcd.c:3402
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff816b4ef0-ffffffff816b57d1: dwc2_hcd_hub_control.constprop.45 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff816c9230)
Location: drivers/usb/dwc2/hcd.c:3430
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff816c9230-ffffffff816c9af1: dwc2_hcd_hub_control.constprop.50 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff81735740)
Location: drivers/usb/dwc2/hcd.c:3439
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff81735740-ffffffff81736015: dwc2_hcd_hub_control.constprop.51 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff817749d0)
Location: drivers/usb/dwc2/hcd.c:3559
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff817749d0-ffffffff8177530f: dwc2_hcd_hub_control.constprop.57 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff81799b10)
Location: drivers/usb/dwc2/hcd.c:3549
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff81799b10-ffffffff8179a6ec: dwc2_hcd_hub_control.constprop.50 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3369
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff817d8f10-ffffffff817d9a55: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
ffffffff817de96b-ffffffff817dea38: dwc2_hcd_hub_control.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3369
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff81809da0-ffffffff8180a8e5: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
ffffffff8180f8a5-ffffffff8180f972: dwc2_hcd_hub_control.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3369
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff818db5c0-ffffffff818dbf78: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
ffffffff818e0603-ffffffff818e06d0: dwc2_hcd_hub_control.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3370
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff818e5480-ffffffff818e5e38: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
ffffffff81c1f67a-ffffffff81c1f747: dwc2_hcd_hub_control.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3409
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff818cd400-ffffffff818cde07: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
ffffffff81c119ba-ffffffff81c11abd: dwc2_hcd_hub_control.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3409
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff819671f0-ffffffff81967d5c: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
ffffffff81d1cf06-ffffffff81d1d22c: dwc2_hcd_hub_control.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3405
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff81ac13b0-ffffffff81ac1e81: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
ffffffff81ee86be-ffffffff81ee8a7e: dwc2_hcd_hub_control.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3376
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff81c4b020-ffffffff81c4bbee: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
ffffffff820a3b8e-ffffffff820a3e9d: dwc2_hcd_hub_control.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3376
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff81cb2640-ffffffff81cb3253: dwc2_hcd_hub_control.isra.0 (STB_LOCAL)
ffffffff82125142-ffffffff8212545a: dwc2_hcd_hub_control.isra.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3376
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff81d67370-ffffffff81d67f83: dwc2_hcd_hub_control.isra.0 (STB_LOCAL)
ffffffff82206916-ffffffff82206c2e: dwc2_hcd_hub_control.isra.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffff800010a42388)
Location: drivers/usb/dwc2/hcd.c:3369
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffff800010a42388-ffff800010a42f90: dwc2_hcd_hub_control.isra.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (c0b15100)
Location: drivers/usb/dwc2/hcd.c:3369
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
c0b15100-c0b15ed0: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (c000000000b04670)
Location: drivers/usb/dwc2/hcd.c:3369
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
c000000000b04670-c000000000b05ab8: dwc2_hcd_hub_control.isra.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffe00065ec68)
Location: drivers/usb/dwc2/hcd.c:3369
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffe00065ec68-ffffffe00065fbf2: dwc2_hcd_hub_control.isra.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3369
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff817c2180-ffffffff817c2cc5: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
ffffffff817c7c85-ffffffff817c7d52: dwc2_hcd_hub_control.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3369
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff817fec20-ffffffff817ff765: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
ffffffff81804725-ffffffff818047f2: dwc2_hcd_hub_control.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3369
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_hub_control
```
**Symbols:**

```
ffffffff81818d30-ffffffff81819875: dwc2_hcd_hub_control.constprop.0 (STB_LOCAL)
ffffffff8181e835-ffffffff8181e902: dwc2_hcd_hub_control.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
