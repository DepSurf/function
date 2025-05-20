# Function: <code>xhci_count_num_dropped_endpoints</code>

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
In drivers/usb/host/xhci.c (ffffffff8164f6a8)
Location: drivers/usb/host/xhci.c:1977
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
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
In drivers/usb/host/xhci.c (ffffffff816b0019)
Location: drivers/usb/host/xhci.c:1955
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
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
In drivers/usb/host/xhci.c (ffffffff816de1b9)
Location: drivers/usb/host/xhci.c:1944
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
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
In drivers/usb/host/xhci.c (ffffffff816f20c9)
Location: drivers/usb/host/xhci.c:1888
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
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
In drivers/usb/host/xhci.c (ffffffff8175e3ab)
Location: drivers/usb/host/xhci.c:1899
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
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
In drivers/usb/host/xhci.c (ffffffff8179ef05)
Location: drivers/usb/host/xhci.c:2025
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
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
In drivers/usb/host/xhci.c (ffffffff817c4fd4)
Location: drivers/usb/host/xhci.c:2042
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
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
In drivers/usb/host/xhci.c (ffffffff81801070)
Location: drivers/usb/host/xhci.c:2071
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81801070-ffffffff81801093: xhci_count_num_dropped_endpoints.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81832120)
Location: drivers/usb/host/xhci.c:2080
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81832120-ffffffff81832143: xhci_count_num_dropped_endpoints.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff819044f0)
Location: drivers/usb/host/xhci.c:2083
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff819044f0-ffffffff81904513: xhci_count_num_dropped_endpoints.constprop.0.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff8190cd70)
Location: drivers/usb/host/xhci.c:2216
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff8190cd70-ffffffff8190cd93: xhci_count_num_dropped_endpoints.constprop.0.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff818f02e0)
Location: drivers/usb/host/xhci.c:2211
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff818f02e0-ffffffff818f0303: xhci_count_num_dropped_endpoints.constprop.0.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff8198cf80)
Location: drivers/usb/host/xhci.c:2223
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff8198cf80-ffffffff8198cfa3: xhci_count_num_dropped_endpoints.constprop.0.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81ae91b0)
Location: drivers/usb/host/xhci.c:2261
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81ae91b0-ffffffff81ae91dd: xhci_count_num_dropped_endpoints.constprop.0.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81c75480)
Location: drivers/usb/host/xhci.c:2259
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81c75480-ffffffff81c754ad: xhci_count_num_dropped_endpoints.constprop.0.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81cdc930)
Location: drivers/usb/host/xhci.c:2099
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81cdc930-ffffffff81cdc95d: xhci_count_num_dropped_endpoints.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81d91950)
Location: drivers/usb/host/xhci.c:2136
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81d91950-ffffffff81d9197d: xhci_count_num_dropped_endpoints.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffff800010a72f54)
Location: drivers/usb/host/xhci.c:2080
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
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
In drivers/usb/host/xhci.c (c0b46c4c)
Location: drivers/usb/host/xhci.c:2080
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
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
In drivers/usb/host/xhci.c (c000000000b489b8)
Location: drivers/usb/host/xhci.c:2080
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
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
In drivers/usb/host/xhci.c (ffffffe00068b43e)
Location: drivers/usb/host/xhci.c:2080
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
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
In drivers/usb/host/xhci.c (ffffffff817ea500)
Location: drivers/usb/host/xhci.c:2080
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff817ea500-ffffffff817ea523: xhci_count_num_dropped_endpoints.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff817af610)
Location: drivers/usb/host/xhci.c:2080
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff817af610-ffffffff817af633: xhci_count_num_dropped_endpoints.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81826fa0)
Location: drivers/usb/host/xhci.c:2080
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81826fa0-ffffffff81826fc3: xhci_count_num_dropped_endpoints.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81840e80)
Location: drivers/usb/host/xhci.c:2080
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81840e80-ffffffff81840ea3: xhci_count_num_dropped_endpoints.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
