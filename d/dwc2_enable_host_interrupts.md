# Function: <code>dwc2_enable_host_interrupts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_enable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816228b0)
Location: drivers/usb/dwc2/core.c:851
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff816228b0-ffffffff81622927: dwc2_enable_host_interrupts (STB_GLOBAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff8168531b)
Location: drivers/usb/dwc2/hcd.c:350
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff816b3542)
Location: drivers/usb/dwc2/hcd.c:351
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff816c7904)
Location: drivers/usb/dwc2/hcd.c:367
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff81733d86)
Location: drivers/usb/dwc2/hcd.c:373
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff81774270)
Location: drivers/usb/dwc2/hcd.c:386
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff81798e43)
Location: drivers/usb/dwc2/hcd.c:380
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffff817d81f5)
Location: drivers/usb/dwc2/hcd.c:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81809085)
Location: drivers/usb/dwc2/hcd.c:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_enable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818d9a90)
Location: drivers/usb/dwc2/hcd.c:190
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818d9a90-ffffffff818d9b10: dwc2_enable_host_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_enable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e39e0)
Location: drivers/usb/dwc2/hcd.c:190
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818e39e0-ffffffff818e3a60: dwc2_enable_host_interrupts (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff818c6e8e)
Location: drivers/usb/dwc2/hcd.c:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffff8196059d)
Location: drivers/usb/dwc2/hcd.c:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81aba989)
Location: drivers/usb/dwc2/hcd.c:184
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81c43df5)
Location: drivers/usb/dwc2/hcd.c:155
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81cab3b5)
Location: drivers/usb/dwc2/hcd.c:155
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81d60065)
Location: drivers/usb/dwc2/hcd.c:155
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffff800010a43270)
Location: drivers/usb/dwc2/hcd.c:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (c0b14ba4)
Location: drivers/usb/dwc2/hcd.c:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (c000000000b03b70)
Location: drivers/usb/dwc2/hcd.c:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffe00065e532)
Location: drivers/usb/dwc2/hcd.c:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffff817c1465)
Location: drivers/usb/dwc2/hcd.c:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffff817fdf05)
Location: drivers/usb/dwc2/hcd.c:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81818015)
Location: drivers/usb/dwc2/hcd.c:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
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
