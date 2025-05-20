# Function: <code>phydev_name</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8164a0a7)
Location: include/linux/phy.h:778
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81679eaa)
Location: include/linux/phy.h:814
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff8167b4c7)
Location: include/linux/phy.h:814
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8168e0da)
Location: include/linux/phy.h:835
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff816903b5)
Location: include/linux/phy.h:835
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816f7b7a)
Location: include/linux/phy.h:858
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff816fa0a3)
Location: include/linux/phy.h:858
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81734d85)
Location: include/linux/phy.h:961
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817377c8)
Location: include/linux/phy.h:961
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81758055)
Location: include/linux/phy.h:970
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff8175a998)
Location: include/linux/phy.h:970
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81794855)
Location: include/linux/phy.h:1057
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81799b17)
Location: include/linux/phy.h:1057
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817b83f5)
Location: include/linux/phy.h:1066
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817bd623)
Location: include/linux/phy.h:1066
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff818806a5)
Location: include/linux/phy.h:1313
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
```
```
In drivers/net/phy/phy_device.c (ffffffff81885ea1)
Location: include/linux/phy.h:1313
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8188d965)
Location: include/linux/phy.h:1442
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
```
```
In drivers/net/phy/phy_device.c (ffffffff81c19344)
Location: include/linux/phy.h:1442
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff818702a5)
Location: include/linux/phy.h:1472
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
```
```
In drivers/net/phy/phy_device.c (ffffffff81c0b24d)
Location: include/linux/phy.h:1472
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81900885)
Location: include/linux/phy.h:1513
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
```
```
In drivers/net/phy/phy_device.c (ffffffff81d10652)
Location: include/linux/phy.h:1513
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81a52545)
Location: include/linux/phy.h:1557
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
```
```
In drivers/net/phy/phy_device.c (ffffffff81edb3d1)
Location: include/linux/phy.h:1557
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdbd45)
Location: include/linux/phy.h:1598
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
```
```
In drivers/net/phy/phy_device.c (ffffffff81be4275)
Location: include/linux/phy.h:1598
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c32e55)
Location: include/linux/phy.h:1758
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3bece)
Location: include/linux/phy.h:1758
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce7b45)
Location: include/linux/phy.h:1798
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf12ce)
Location: include/linux/phy.h:1798
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffff8000109d0e00)
Location: include/linux/phy.h:1066
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffff8000109d69f4)
Location: include/linux/phy.h:1066
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c0ab8e18)
Location: include/linux/phy.h:1066
Inline: True
```
```
In drivers/net/phy/phy_device.c (c0abe348)
Location: include/linux/phy.h:1066
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acffb0)
Location: include/linux/phy.h:1066
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c000000000a904fc)
Location: include/linux/phy.h:1066
Inline: True
```
```
In drivers/net/phy/phy_device.c (c000000000a98164)
Location: include/linux/phy.h:1066
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffe00061d8b0)
Location: include/linux/phy.h:1066
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffe000622a5e)
Location: include/linux/phy.h:1066
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8177cec5)
Location: include/linux/phy.h:1066
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817820f3)
Location: include/linux/phy.h:1066
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8175cc75)
Location: include/linux/phy.h:1066
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81761e83)
Location: include/linux/phy.h:1066
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817ad275)
Location: include/linux/phy.h:1066
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817b24a3)
Location: include/linux/phy.h:1066
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817c7205)
Location: include/linux/phy.h:1066
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817cc433)
Location: include/linux/phy.h:1066
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/net/phy/phy_device.c:phy_scan_fixups
```
</details>
</li>
</ul>

## Differences
