# Function: <code>dwc2_gahbcfg_init</code>

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
In drivers/usb/dwc2/core.c (ffffffff816223db)
Location: drivers/usb/dwc2/core.c:683
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81685ce8)
Location: drivers/usb/dwc2/hcd.c:264
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff816b3f3a)
Location: drivers/usb/dwc2/hcd.c:265
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff816c82eb)
Location: drivers/usb/dwc2/hcd.c:281
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff817347bb)
Location: drivers/usb/dwc2/hcd.c:287
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff8177663d)
Location: drivers/usb/dwc2/hcd.c:290
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff8179c10e)
Location: drivers/usb/dwc2/hcd.c:290
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff817db13e)
Location: drivers/usb/dwc2/hcd.c:100
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff8180c05e)
Location: drivers/usb/dwc2/hcd.c:100
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_gahbcfg_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:100
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff818d9630-ffffffff818d971a: dwc2_gahbcfg_init (STB_LOCAL)
ffffffff818e0444-ffffffff818e045d: dwc2_gahbcfg_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_gahbcfg_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:100
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff818e3580-ffffffff818e366a: dwc2_gahbcfg_init (STB_LOCAL)
ffffffff81c1f4bb-ffffffff81c1f4d4: dwc2_gahbcfg_init.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff818c8da0)
Location: drivers/usb/dwc2/hcd.c:98
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81961964)
Location: drivers/usb/dwc2/hcd.c:98
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81abbda6)
Location: drivers/usb/dwc2/hcd.c:98
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81c45340)
Location: drivers/usb/dwc2/hcd.c:69
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81cac926)
Location: drivers/usb/dwc2/hcd.c:69
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81d615d6)
Location: drivers/usb/dwc2/hcd.c:69
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffff800010a4476c)
Location: drivers/usb/dwc2/hcd.c:100
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (c0b16f14)
Location: drivers/usb/dwc2/hcd.c:100
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (c000000000b07770)
Location: drivers/usb/dwc2/hcd.c:100
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffe000660eb4)
Location: drivers/usb/dwc2/hcd.c:100
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff817c443e)
Location: drivers/usb/dwc2/hcd.c:100
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81800ede)
Location: drivers/usb/dwc2/hcd.c:100
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff8181afee)
Location: drivers/usb/dwc2/hcd.c:100
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
