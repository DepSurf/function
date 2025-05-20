# Function: <code>dev_pm_opp_find_freq_floor</code>

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
In drivers/devfreq/devfreq.c (0)
Location: include/linux/pm_opp.h:95
Inline: True
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
In drivers/devfreq/devfreq.c (0)
Location: include/linux/pm_opp.h:119
Inline: True
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
In drivers/devfreq/devfreq.c (0)
Location: include/linux/pm_opp.h:173
Inline: True
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
In drivers/devfreq/devfreq.c (0)
Location: include/linux/pm_opp.h:187
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4680)
Location: drivers/opp/core.c:480
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff817d4680-ffffffff817d476f: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181da60)
Location: drivers/opp/core.c:487
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff8181da60-ffffffff8181db5b: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81849750)
Location: drivers/opp/core.c:471
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81849750-ffffffff8184984b: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:486
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff8188d7b0-ffffffff8188d7d2: dev_pm_opp_find_freq_floor.cold (STB_LOCAL)
ffffffff8188c4d0-ffffffff8188c59e: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:534
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff818bf9b2-ffffffff818bf9d4: dev_pm_opp_find_freq_floor.cold (STB_LOCAL)
ffffffff818be640-ffffffff818be70e: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:534
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81991553-ffffffff81991597: dev_pm_opp_find_freq_floor.cold (STB_LOCAL)
ffffffff8198ef40-ffffffff8198f0a1: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:534
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81c29315-ffffffff81c29359: dev_pm_opp_find_freq_floor.cold (STB_LOCAL)
ffffffff81992f10-ffffffff81993071: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:613
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81c1b45a-ffffffff81c1b49e: dev_pm_opp_find_freq_floor.cold (STB_LOCAL)
ffffffff81977800-ffffffff81977961: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:613
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81d2b597-ffffffff81d2b5fd: dev_pm_opp_find_freq_floor.cold (STB_LOCAL)
ffffffff81a206b0-ffffffff81a20869: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:541
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81ef7722-ffffffff81ef7776: dev_pm_opp_find_freq_floor.cold (STB_LOCAL)
ffffffff81b89100-ffffffff81b892ae: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d283b0)
Location: drivers/opp/core.c:674
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81d283b0-ffffffff81d283ec: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d91550)
Location: drivers/opp/core.c:677
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81d91550-ffffffff81d9158c: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e48da0)
Location: drivers/opp/core.c:732
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
```
**Symbols:**

```
ffffffff81e48da0-ffffffff81e48ddc: dev_pm_opp_find_freq_floor (STB_GLOBAL)
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
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b19658)
Location: drivers/opp/core.c:534
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffff800010b19658-ffff800010b19774: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf43f4)
Location: drivers/opp/core.c:534
Inline: False
Direct callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/devfreq/devfreq.c:find_available_max_freq
```
**Symbols:**

```
c0bf43f4-c0bf44e4: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0b000)
Location: drivers/opp/core.c:534
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/devfreq/devfreq.c:find_available_max_freq
```
**Symbols:**

```
c000000000c0b000-c000000000c0b168: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701ff0)
Location: drivers/opp/core.c:534
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/devfreq/devfreq.c:find_available_max_freq
```
**Symbols:**

```
ffffffe000701ff0-ffffffe0007020d4: dev_pm_opp_find_freq_floor (STB_GLOBAL)
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
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:534
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff818640d2-ffffffff818640f4: dev_pm_opp_find_freq_floor.cold (STB_LOCAL)
ffffffff81862d60-ffffffff81862e2e: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:534
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff8182cd82-ffffffff8182cda4: dev_pm_opp_find_freq_floor.cold (STB_LOCAL)
ffffffff8182ba10-ffffffff8182bade: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:534
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff818b4e62-ffffffff818b4e84: dev_pm_opp_find_freq_floor.cold (STB_LOCAL)
ffffffff818b3af0-ffffffff818b3bbe: dev_pm_opp_find_freq_floor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_floor(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:534
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff818d1112-ffffffff818d1134: dev_pm_opp_find_freq_floor.cold (STB_LOCAL)
ffffffff818cfda0-ffffffff818cfe6e: dev_pm_opp_find_freq_floor (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
