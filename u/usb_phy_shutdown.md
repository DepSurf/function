# Function: <code>usb_phy_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8160da4c)
Location: include/linux/usb/phy.h:175
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/dwc2/platform.c (ffffffff81626328)
Location: include/linux/usb/phy.h:175
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8166d604)
Location: include/linux/usb/phy.h:175
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/dwc2/platform.c (ffffffff81684748)
Location: include/linux/usb/phy.h:175
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/core/hcd.c (ffffffff8169b304)
Location: include/linux/usb/phy.h:175
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/dwc2/platform.c (ffffffff816b0d1b)
Location: include/linux/usb/phy.h:175
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/core/hcd.c (ffffffff816b0664)
Location: include/linux/usb/phy.h:182
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/dwc2/platform.c (ffffffff816c5e7b)
Location: include/linux/usb/phy.h:182
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/core/hcd.c (ffffffff8171bc7a)
Location: include/linux/usb/phy.h:208
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/dwc2/platform.c (ffffffff8173216b)
Location: include/linux/usb/phy.h:208
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff81771a6b)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff81796b3b)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff817d5bab)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff81806a5b)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff818d727b)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff818e12cd)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff818c4530)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff8195bfc0)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff81ab5d2c)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff81c3e64c)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff81ca5a7e)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff81d5a6ce)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffff800010a3e230)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (c0b10e3c)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/musb/musb_core.c (c0b6556c)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_remove
  - drivers/usb/musb/musb_core.c:musb_init_controller
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
In drivers/usb/dwc2/platform.c (c000000000afe014)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffe00065a1d0)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff817bee3b)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff817fb8db)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
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
In drivers/usb/dwc2/platform.c (ffffffff818159eb)
Location: include/linux/usb/phy.h:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
</details>
</li>
</ul>

## Differences
