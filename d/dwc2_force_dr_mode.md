# Function: <code>dwc2_force_dr_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81682050)
Location: drivers/usb/dwc2/core.c:366
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81682050-ffffffff816820df: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816aff30)
Location: drivers/usb/dwc2/core.c:464
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff816aff30-ffffffff816aff90: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816c5100)
Location: drivers/usb/dwc2/core.c:464
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff816c5100-ffffffff816c5160: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817313e0)
Location: drivers/usb/dwc2/core.c:465
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff817313e0-ffffffff81731440: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81770550)
Location: drivers/usb/dwc2/core.c:642
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81770550-ffffffff81770608: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81794b20)
Location: drivers/usb/dwc2/core.c:642
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81794b20-ffffffff81794c05: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:642
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff817d4309-ffffffff817d4324: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff817d3380-ffffffff817d347a: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:642
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff818051b3-ffffffff818051ce: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff81804250-ffffffff8180434a: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:657
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff818d5bd0-ffffffff818d5beb: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff818d5240-ffffffff818d5298: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:657
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81c1ecd2-ffffffff81c1eced: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff818df560-ffffffff818df5b8: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:601
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81c10ae2-ffffffff81c10afd: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff818c2640-ffffffff818c2749: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:601
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81d18556-ffffffff81d185e1: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff819594f0-ffffffff81959659: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:601
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81ee34f5-ffffffff81ee35a0: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff81ab3330-ffffffff81ab34a9: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:571
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff8209f670-ffffffff8209f700: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff81c3bac0-ffffffff81c3bc2a: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:571
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff82120c26-ffffffff82120cb6: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff81ca2e90-ffffffff81ca3027: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:571
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff822023fd-ffffffff8220248d: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff81d57ae0-ffffffff81d57c77: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3ae98)
Location: drivers/usb/dwc2/core.c:642
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffff800010a3ae98-ffff800010a3b020: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0e718)
Location: drivers/usb/dwc2/core.c:642
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
c0b0e718-c0b0e854: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000af8b30)
Location: drivers/usb/dwc2/core.c:642
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
c000000000af8b30-c000000000af8e2c: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe0006561d2)
Location: drivers/usb/dwc2/core.c:642
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffe0006561d2-ffffffe0006563d2: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:642
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff817bd593-ffffffff817bd5ae: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff817bc630-ffffffff817bc72a: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:642
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff817fa033-ffffffff817fa04e: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff817f90d0-ffffffff817f91ca: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dwc2_force_dr_mode(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:642
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81814273-ffffffff8181428e: dwc2_force_dr_mode.cold (STB_LOCAL)
ffffffff81813310-ffffffff8181340a: dwc2_force_dr_mode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
