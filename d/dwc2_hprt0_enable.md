# Function: <code>dwc2_hprt0_enable</code>

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
In drivers/usb/dwc2/hcd_intr.c (ffffffff8162cde1)
Location: drivers/usb/dwc2/hcd_intr.c:236
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff8168d16f)
Location: drivers/usb/dwc2/hcd_intr.c:256
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff816bb25a)
Location: drivers/usb/dwc2/hcd_intr.c:256
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff816cf401)
Location: drivers/usb/dwc2/hcd_intr.c:256
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff8173ba4d)
Location: drivers/usb/dwc2/hcd_intr.c:257
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177c1f1)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a2694)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff817e13e6)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff818122d6)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_hprt0_enable(struct dwc2_hsotg *hsotg, u32 hprt0, u32 *hprt0_modify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e0b60)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
```
**Symbols:**

```
ffffffff818e0b60-ffffffff818e0d22: dwc2_hprt0_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_hprt0_enable(struct dwc2_hsotg *hsotg, u32 hprt0, u32 *hprt0_modify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818ea3d0)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
```
**Symbols:**

```
ffffffff818ea3d0-ffffffff818ea58e: dwc2_hprt0_enable (STB_LOCAL)
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff818ce1e0)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
```
**Symbols:**

```
ffffffff818ce1e0-ffffffff818ce3b1: dwc2_hprt0_enable.constprop.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff81968f80-ffffffff81969236: dwc2_hprt0_enable.constprop.0 (STB_LOCAL)
ffffffff81d1d726-ffffffff81d1d837: dwc2_hprt0_enable.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff81ac3170-ffffffff81ac343a: dwc2_hprt0_enable.constprop.0 (STB_LOCAL)
ffffffff81ee906f-ffffffff81ee9180: dwc2_hprt0_enable.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:233
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff81c4d090-ffffffff81c4d35a: dwc2_hprt0_enable.constprop.0 (STB_LOCAL)
ffffffff820a4374-ffffffff820a4485: dwc2_hprt0_enable.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:233
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff81cb4700-ffffffff81cb49ca: dwc2_hprt0_enable.constprop.0 (STB_LOCAL)
ffffffff82125931-ffffffff82125a42: dwc2_hprt0_enable.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:233
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff81d69430-ffffffff81d696fa: dwc2_hprt0_enable.constprop.0 (STB_LOCAL)
ffffffff82207105-ffffffff82207216: dwc2_hprt0_enable.constprop.0.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd_intr.c (ffff800010a4b66c)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (c0b1d8a8)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (c000000000b122cc)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffe0006684e0)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff817ca6b6)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff81807156)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff81821262)
Location: drivers/usb/dwc2/hcd_intr.c:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
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
