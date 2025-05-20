# Function: <code>dev_pm_opp_get_freq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d3ec0)
Location: drivers/opp/core.c:119
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffff817d3ec0-ffffffff817d3ef9: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181cca0)
Location: drivers/opp/core.c:117
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffff8181cca0-ffffffff8181ccd9: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848860)
Location: drivers/opp/core.c:122
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffff81848860-ffffffff81848899: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8188d5b0)
Location: drivers/opp/core.c:119
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffff8188d5b0-ffffffff8188d5ca: dev_pm_opp_get_freq.cold (STB_LOCAL)
ffffffff8188b8b0-ffffffff8188b8e0: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818bf79e)
Location: drivers/opp/core.c:119
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffff818bf79e-ffffffff818bf7b8: dev_pm_opp_get_freq.cold (STB_LOCAL)
ffffffff818bd990-ffffffff818bd9c0: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8198e960)
Location: drivers/opp/core.c:119
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffff8199121e-ffffffff81991238: dev_pm_opp_get_freq.cold (STB_LOCAL)
ffffffff8198de20-ffffffff8198de50: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81992740)
Location: drivers/opp/core.c:119
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffff81c28f26-ffffffff81c28f40: dev_pm_opp_get_freq.cold (STB_LOCAL)
ffffffff81991810-ffffffff81991835: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81976da0)
Location: drivers/opp/core.c:123
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81c1b12b-ffffffff81c1b146: dev_pm_opp_get_freq.cold (STB_LOCAL)
ffffffff81975e30-ffffffff81975e50: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81d2b323)
Location: drivers/opp/core.c:123
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81d2b138-ffffffff81d2b153: dev_pm_opp_get_freq.cold (STB_LOCAL)
ffffffff81a1ebe0-ffffffff81a1ec00: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81ef7500)
Location: drivers/opp/core.c:148
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
Direct callers:
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
**Symbols:**

```
ffffffff81ef737d-ffffffff81ef73a0: dev_pm_opp_get_freq.cold (STB_LOCAL)
ffffffff81b87740-ffffffff81b87768: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff820a8ad3)
Location: drivers/opp/core.c:189
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
Direct callers:
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
**Symbols:**

```
ffffffff81d266c0-ffffffff81d26720: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff82129ca9)
Location: drivers/opp/core.c:186
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
Direct callers:
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
**Symbols:**

```
ffffffff81d8f8f0-ffffffff81d8f950: dev_pm_opp_get_freq (STB_GLOBAL)
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
In drivers/opp/core.c (ffffffff8220b9f2)
Location: include/linux/pm_opp.h:691
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
```
In drivers/devfreq/governor_passive.c (ffffffff81ea73d7)
Location: include/linux/pm_opp.h:691
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18708)
Location: drivers/opp/core.c:119
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffff800010b18708-ffff800010b18764: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3740)
Location: drivers/opp/core.c:119
Inline: True
Direct callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
```
**Symbols:**

```
c0bf3740-c0bf3794: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09f40)
Location: drivers/opp/core.c:119
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
c000000000c09f40-c000000000c09fb0: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701382)
Location: drivers/opp/core.c:119
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffe000701382-ffffffe0007013ce: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81863ebe)
Location: drivers/opp/core.c:119
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffff81863ebe-ffffffff81863ed8: dev_pm_opp_get_freq.cold (STB_LOCAL)
ffffffff818620b0-ffffffff818620e0: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8182cb6e)
Location: drivers/opp/core.c:119
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffff8182cb6e-ffffffff8182cb88: dev_pm_opp_get_freq.cold (STB_LOCAL)
ffffffff8182ad60-ffffffff8182ad90: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818b4c4e)
Location: drivers/opp/core.c:119
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffff818b4c4e-ffffffff818b4c68: dev_pm_opp_get_freq.cold (STB_LOCAL)
ffffffff818b2e40-ffffffff818b2e70: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_freq(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818d0efe)
Location: drivers/opp/core.c:119
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
```
**Symbols:**

```
ffffffff818d0efe-ffffffff818d0f18: dev_pm_opp_get_freq.cold (STB_LOCAL)
ffffffff818cf0f0-ffffffff818cf120: dev_pm_opp_get_freq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
