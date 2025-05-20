# Function: <code>process_bulk_intr_td</code>

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
In drivers/usb/host/xhci-ring.c (ffffffff8165b2a5)
Location: drivers/usb/host/xhci-ring.c:2135
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff816bbb55)
Location: drivers/usb/host/xhci-ring.c:2164
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff816e9e8c)
Location: drivers/usb/host/xhci-ring.c:2168
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff816fe1d1)
Location: drivers/usb/host/xhci-ring.c:2217
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff8176ad4f)
Location: drivers/usb/host/xhci-ring.c:2211
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff817ac09e)
Location: drivers/usb/host/xhci-ring.c:2131
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff817d21d8)
Location: drivers/usb/host/xhci-ring.c:2179
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff81811c7f)
Location: drivers/usb/host/xhci-ring.c:2225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff81842e3f)
Location: drivers/usb/host/xhci-ring.c:2225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2258
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81912ba0-ffffffff81912db2: process_bulk_intr_td.isra.0 (STB_LOCAL)
ffffffff81916ebc-ffffffff81916f7a: process_bulk_intr_td.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2263
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff8191a210-ffffffff8191a430: process_bulk_intr_td.isra.0 (STB_LOCAL)
ffffffff81c21dde-ffffffff81c21e9c: process_bulk_intr_td.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2446
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff818fd590-ffffffff818fd793: process_bulk_intr_td.isra.0 (STB_LOCAL)
ffffffff81c13e46-ffffffff81c13f10: process_bulk_intr_td.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2511
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff8199c700-ffffffff8199c900: process_bulk_intr_td.isra.0 (STB_LOCAL)
ffffffff81d20d8c-ffffffff81d20e53: process_bulk_intr_td.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2445
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81af9c30-ffffffff81af9e3c: process_bulk_intr_td.isra.0 (STB_LOCAL)
ffffffff81eec8f7-ffffffff81eec9b0: process_bulk_intr_td.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81c87e30)
Location: drivers/usb/host/xhci-ring.c:2445
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81c87e30-ffffffff81c880fc: process_bulk_intr_td.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81cef010)
Location: drivers/usb/host/xhci-ring.c:2465
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81cef010-ffffffff81cef2d7: process_bulk_intr_td.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81da4830)
Location: drivers/usb/host/xhci-ring.c:2489
Inline: True
```
**Symbols:**

```
ffffffff81da4830-ffffffff81da4af7: process_bulk_intr_td.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffff800010a81c60)
Location: drivers/usb/host/xhci-ring.c:2225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (c0b5529c)
Location: drivers/usb/host/xhci-ring.c:2225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (c000000000b5b408)
Location: drivers/usb/host/xhci-ring.c:2225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffe0006982ec)
Location: drivers/usb/host/xhci-ring.c:2225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff817fb1ef)
Location: drivers/usb/host/xhci-ring.c:2225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff817c038f)
Location: drivers/usb/host/xhci-ring.c:2225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff81837cbf)
Location: drivers/usb/host/xhci-ring.c:2225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
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
In drivers/usb/host/xhci-ring.c (ffffffff818520ef)
Location: drivers/usb/host/xhci-ring.c:2225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
</details>
</li>
</ul>

## Differences
