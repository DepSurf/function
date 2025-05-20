# Function: <code>dwc2_clear_force_mode</code>

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
In drivers/usb/dwc2/core.c (ffffffff81683a8a)
Location: drivers/usb/dwc2/core.c:347
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dwc2_clear_force_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816afef0)
Location: drivers/usb/dwc2/core.c:448
Inline: True
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff816afef0-ffffffff816aff2c: dwc2_clear_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dwc2_clear_force_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816c50c0)
Location: drivers/usb/dwc2/core.c:448
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff816c50c0-ffffffff816c50f7: dwc2_clear_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dwc2_clear_force_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817313a0)
Location: drivers/usb/dwc2/core.c:449
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff817313a0-ffffffff817313d7: dwc2_clear_force_mode (STB_GLOBAL)
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
In drivers/usb/dwc2/core.c (ffffffff817705b0)
Location: drivers/usb/dwc2/core.c:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffff81794b8b)
Location: drivers/usb/dwc2/core.c:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffff817d33a2)
Location: drivers/usb/dwc2/core.c:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffff81804272)
Location: drivers/usb/dwc2/core.c:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_clear_force_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d4550)
Location: drivers/usb/dwc2/core.c:636
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
```
**Symbols:**

```
ffffffff818d4550-ffffffff818d45df: dwc2_clear_force_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_clear_force_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818de870)
Location: drivers/usb/dwc2/core.c:636
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
```
**Symbols:**

```
ffffffff818de870-ffffffff818de8ff: dwc2_clear_force_mode (STB_LOCAL)
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
In drivers/usb/dwc2/core.c (ffffffff818c2662)
Location: drivers/usb/dwc2/core.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffff8195951b)
Location: drivers/usb/dwc2/core.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffff81ab335d)
Location: drivers/usb/dwc2/core.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffff81c3bb75)
Location: drivers/usb/dwc2/core.c:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffff81ca2f0b)
Location: drivers/usb/dwc2/core.c:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffff81d57b5b)
Location: drivers/usb/dwc2/core.c:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffff800010a3aec4)
Location: drivers/usb/dwc2/core.c:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (c0b0e744)
Location: drivers/usb/dwc2/core.c:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (c000000000af8b64)
Location: drivers/usb/dwc2/core.c:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffe0006561f8)
Location: drivers/usb/dwc2/core.c:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffff817bc652)
Location: drivers/usb/dwc2/core.c:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffff817f90f2)
Location: drivers/usb/dwc2/core.c:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
In drivers/usb/dwc2/core.c (ffffffff81813332)
Location: drivers/usb/dwc2/core.c:621
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
