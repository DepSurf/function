# Function: <code>dev_pm_opp_find_freq_ceil</code>

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
Location: include/linux/pm_opp.h:101
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
Location: include/linux/pm_opp.h:125
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
Location: include/linux/pm_opp.h:179
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
Location: include/linux/pm_opp.h:193
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4600)
Location: drivers/opp/core.c:439
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff817d4600-ffffffff817d4673: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181d3c0)
Location: drivers/opp/core.c:446
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff8181d3c0-ffffffff8181d437: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818491b0)
Location: drivers/opp/core.c:430
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff818491b0-ffffffff81849227: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8188d63d)
Location: drivers/opp/core.c:445
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8188d63d-ffffffff8188d65f: dev_pm_opp_find_freq_ceil.cold (STB_LOCAL)
ffffffff8188c070-ffffffff8188c0cd: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818bf84b)
Location: drivers/opp/core.c:493
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818bf84b-ffffffff818bf86d: dev_pm_opp_find_freq_ceil.cold (STB_LOCAL)
ffffffff818be1e0-ffffffff818be23d: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8199140a)
Location: drivers/opp/core.c:493
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:set_freq_table
```
**Symbols:**

```
ffffffff819913eb-ffffffff8199142f: dev_pm_opp_find_freq_ceil.cold (STB_LOCAL)
ffffffff8198e820-ffffffff8198e8c1: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81c2914c)
Location: drivers/opp/core.c:493
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:set_freq_table
```
**Symbols:**

```
ffffffff81c2912d-ffffffff81c29171: dev_pm_opp_find_freq_ceil.cold (STB_LOCAL)
ffffffff81992600-ffffffff819926a1: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81c1b260)
Location: drivers/opp/core.c:572
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81c1b241-ffffffff81c1b285: dev_pm_opp_find_freq_ceil.cold (STB_LOCAL)
ffffffff81976c60-ffffffff81976d01: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81d2b2df)
Location: drivers/opp/core.c:572
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81d2b2c0-ffffffff81d2b304: dev_pm_opp_find_freq_ceil.cold (STB_LOCAL)
ffffffff81a1fa30-ffffffff81a1fad1: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81ef74a7)
Location: drivers/opp/core.c:500
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81ef74a7-ffffffff81ef74e1: dev_pm_opp_find_freq_ceil.cold (STB_LOCAL)
ffffffff81b885a0-ffffffff81b88655: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d28240)
Location: drivers/opp/core.c:649
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81d28240-ffffffff81d2827c: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d913e0)
Location: drivers/opp/core.c:652
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
```
**Symbols:**

```
ffffffff81d913e0-ffffffff81d9141c: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e48b30)
Location: drivers/opp/core.c:679
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff81e48b30-ffffffff81e48b6c: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
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
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b190b0)
Location: drivers/opp/core.c:493
Inline: True
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffff800010b190b0-ffff800010b1913c: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3e98)
Location: drivers/opp/core.c:493
Inline: True
Direct callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:dfll_calculate_rate_request
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/cpufreq/omap-cpufreq.c:omap_target
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:find_available_min_freq
```
**Symbols:**

```
c0bf3e98-c0bf3f0c: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0ab50)
Location: drivers/opp/core.c:493
Inline: True
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:find_available_min_freq
```
**Symbols:**

```
c000000000c0ab50-c000000000c0abf8: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701b44)
Location: drivers/opp/core.c:493
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:find_available_min_freq
```
**Symbols:**

```
ffffffe000701b44-ffffffe000701bbc: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
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
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81863f6b)
Location: drivers/opp/core.c:493
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81863f6b-ffffffff81863f8d: dev_pm_opp_find_freq_ceil.cold (STB_LOCAL)
ffffffff81862900-ffffffff8186295d: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8182cc1b)
Location: drivers/opp/core.c:493
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8182cc1b-ffffffff8182cc3d: dev_pm_opp_find_freq_ceil.cold (STB_LOCAL)
ffffffff8182b5b0-ffffffff8182b60d: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818b4cfb)
Location: drivers/opp/core.c:493
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818b4cfb-ffffffff818b4d1d: dev_pm_opp_find_freq_ceil.cold (STB_LOCAL)
ffffffff818b3690-ffffffff818b36ed: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_freq_ceil(struct device *dev, long unsigned int *freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818d0fab)
Location: drivers/opp/core.c:493
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818d0fab-ffffffff818d0fcd: dev_pm_opp_find_freq_ceil.cold (STB_LOCAL)
ffffffff818cf940-ffffffff818cf99d: dev_pm_opp_find_freq_ceil (STB_GLOBAL)
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
