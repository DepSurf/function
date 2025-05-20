# Function: <code>dwc2_core_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81621bb0)
Location: drivers/usb/dwc2/core.c:484
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
```
**Symbols:**

```
ffffffff81621bb0-ffffffff81621cf9: dwc2_core_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81681fa0)
Location: drivers/usb/dwc2/core.c:245
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode
```
**Symbols:**

```
ffffffff81681fa0-ffffffff8168204a: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816afdd0)
Location: drivers/usb/dwc2/core.c:316
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode
```
**Symbols:**

```
ffffffff816afdd0-ffffffff816afeed: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816c4fa0)
Location: drivers/usb/dwc2/core.c:316
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode
```
**Symbols:**

```
ffffffff816c4fa0-ffffffff816c50bf: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81731280)
Location: drivers/usb/dwc2/core.c:317
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset_and_force_dr_mode
```
**Symbols:**

```
ffffffff81731280-ffffffff8173139f: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81770370)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff81770370-ffffffff8177048f: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81795320)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff81795320-ffffffff8179544e: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff817d4324-ffffffff817d4366: dwc2_core_reset.cold (STB_LOCAL)
ffffffff817d3ba0-ffffffff817d3ca1: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff818051ce-ffffffff81805210: dwc2_core_reset.cold (STB_LOCAL)
ffffffff81804a70-ffffffff81804b71: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d4e00)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff818d4e00-ffffffff818d4ff4: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818df120)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff818df120-ffffffff818df314: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c2220)
Location: drivers/usb/dwc2/core.c:423
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff818c2220-ffffffff818c2426: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:423
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff81d1835a-ffffffff81d1847d: dwc2_core_reset.cold (STB_LOCAL)
ffffffff81958f50-ffffffff8195922c: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:423
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff81ee32b0-ffffffff81ee341f: dwc2_core_reset.cold (STB_LOCAL)
ffffffff81ab2db0-ffffffff81ab3046: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:393
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff8209f471-ffffffff8209f5cf: dwc2_core_reset.cold (STB_LOCAL)
ffffffff81c3b4f0-ffffffff81c3b789: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:393
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff82120a21-ffffffff82120b7f: dwc2_core_reset.cold (STB_LOCAL)
ffffffff81ca28a0-ffffffff81ca2b39: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:393
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff822021f8-ffffffff82202356: dwc2_core_reset.cold (STB_LOCAL)
ffffffff81d574f0-ffffffff81d57789: dwc2_core_reset (STB_GLOBAL)
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
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3bb98)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffff800010a3bb98-ffff800010a3bd38: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0e410)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
c0b0e410-c0b0e5b4: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000afa140)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
c000000000afa140-c000000000afa450: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe000657270)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffe000657270-ffffffe00065744e: dwc2_core_reset (STB_GLOBAL)
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
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff817bd5ae-ffffffff817bd5f0: dwc2_core_reset.cold (STB_LOCAL)
ffffffff817bce50-ffffffff817bcf51: dwc2_core_reset (STB_GLOBAL)
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
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff817fa04e-ffffffff817fa090: dwc2_core_reset.cold (STB_LOCAL)
ffffffff817f98f0-ffffffff817f99f1: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_core_reset(struct dwc2_hsotg *hsotg, bool skip_wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:495
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff8181428e-ffffffff818142d0: dwc2_core_reset.cold (STB_LOCAL)
ffffffff81813b30-ffffffff81813c31: dwc2_core_reset (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool skip_wait</code>
</li>
</ul>
</details>
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
