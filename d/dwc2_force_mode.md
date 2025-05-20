# Function: <code>dwc2_force_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81681b80)
Location: drivers/usb/dwc2/core.c:307
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
```
**Symbols:**

```
ffffffff81681b80-ffffffff81681c7b: dwc2_force_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816af9a0)
Location: drivers/usb/dwc2/core.c:402
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed
```
**Symbols:**

```
ffffffff816af9a0-ffffffff816afaa3: dwc2_force_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816c4b90)
Location: drivers/usb/dwc2/core.c:402
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed
```
**Symbols:**

```
ffffffff816c4b90-ffffffff816c4c59: dwc2_force_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81730e70)
Location: drivers/usb/dwc2/core.c:403
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed
```
**Symbols:**

```
ffffffff81730e70-ffffffff81730f39: dwc2_force_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81770490)
Location: drivers/usb/dwc2/core.c:573
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff81770490-ffffffff81770550: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81794a10)
Location: drivers/usb/dwc2/core.c:573
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff81794a10-ffffffff81794b15: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817d32ae)
Location: drivers/usb/dwc2/core.c:573
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff817d42e3-ffffffff817d4309: dwc2_force_mode.cold (STB_LOCAL)
ffffffff817d3270-ffffffff817d3371: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81804140)
Location: drivers/usb/dwc2/core.c:573
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff81804140-ffffffff8180424a: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d5130)
Location: drivers/usb/dwc2/core.c:588
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff818d5130-ffffffff818d523a: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818df450)
Location: drivers/usb/dwc2/core.c:588
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff818df450-ffffffff818df55a: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c2530)
Location: drivers/usb/dwc2/core.c:532
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff818c2530-ffffffff818c2640: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:532
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff81d18508-ffffffff81d18556: dwc2_force_mode.cold (STB_LOCAL)
ffffffff819593a0-ffffffff819594e2: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:532
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff81ee34a8-ffffffff81ee34f5: dwc2_force_mode.cold (STB_LOCAL)
ffffffff81ab31c0-ffffffff81ab3328: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:502
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff8209f623-ffffffff8209f670: dwc2_force_mode.cold (STB_LOCAL)
ffffffff81c3b940-ffffffff81c3baa8: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:502
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff82120bd9-ffffffff82120c26: dwc2_force_mode.cold (STB_LOCAL)
ffffffff81ca2d10-ffffffff81ca2e78: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:502
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff822023b0-ffffffff822023fd: dwc2_force_mode.cold (STB_LOCAL)
ffffffff81d57960-ffffffff81d57ac8: dwc2_force_mode (STB_GLOBAL)
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
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3ad38)
Location: drivers/usb/dwc2/core.c:573
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffff800010a3ad38-ffff800010a3ae98: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0e5b4)
Location: drivers/usb/dwc2/core.c:573
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
c0b0e5b4-c0b0e718: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000af8830)
Location: drivers/usb/dwc2/core.c:573
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
c000000000af8830-c000000000af8b30: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe00065600c)
Location: drivers/usb/dwc2/core.c:573
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffe00065600c-ffffffe0006561d2: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817bc520)
Location: drivers/usb/dwc2/core.c:573
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff817bc520-ffffffff817bc62a: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817f8fc0)
Location: drivers/usb/dwc2/core.c:573
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff817f8fc0-ffffffff817f90ca: dwc2_force_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg *hsotg, bool host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81813200)
Location: drivers/usb/dwc2/core.c:573
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
**Symbols:**

```
ffffffff81813200-ffffffff8181330a: dwc2_force_mode (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
