# Function: <code>dev_pm_opp_get_voltage</code>

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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d3e80)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff817d3e80-ffffffff817d3eb6: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181cc60)
Location: drivers/opp/core.c:99
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff8181cc60-ffffffff8181cc96: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848820)
Location: drivers/opp/core.c:104
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81848820-ffffffff81848856: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8188d596)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff8188d596-ffffffff8188d5b0: dev_pm_opp_get_voltage.cold (STB_LOCAL)
ffffffff8188b880-ffffffff8188b8a8: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818bf784)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff818bf784-ffffffff818bf79e: dev_pm_opp_get_voltage.cold (STB_LOCAL)
ffffffff818bd960-ffffffff818bd988: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81991204)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
```
**Symbols:**

```
ffffffff81991204-ffffffff8199121e: dev_pm_opp_get_voltage.cold (STB_LOCAL)
ffffffff8198ddf0-ffffffff8198de18: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81c28f0c)
Location: drivers/opp/core.c:101
Inline: True
```
**Symbols:**

```
ffffffff81c28f0c-ffffffff81c28f26: dev_pm_opp_get_voltage.cold (STB_LOCAL)
ffffffff819917e0-ffffffff81991808: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81c1b110)
Location: drivers/opp/core.c:105
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81c1b110-ffffffff81c1b12b: dev_pm_opp_get_voltage.cold (STB_LOCAL)
ffffffff81975e00-ffffffff81975e23: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81d2b11d)
Location: drivers/opp/core.c:105
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81d2b11d-ffffffff81d2b138: dev_pm_opp_get_voltage.cold (STB_LOCAL)
ffffffff81a1ebb0-ffffffff81a1ebd3: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81ef72c7)
Location: drivers/opp/core.c:105
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81ef72c7-ffffffff81ef72ea: dev_pm_opp_get_voltage.cold (STB_LOCAL)
ffffffff81b87510-ffffffff81b8753b: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d26f70)
Location: drivers/opp/core.c:121
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81d26f70-ffffffff81d26fb6: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d90170)
Location: drivers/opp/core.c:118
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81d90170-ffffffff81d901b6: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e47800)
Location: drivers/opp/core.c:118
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
**Symbols:**

```
ffffffff81e47800-ffffffff81e47846: dev_pm_opp_get_voltage (STB_GLOBAL)
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b186b0)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffff800010b186b0-ffff800010b18708: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf36f4)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:dfll_calculate_rate_request
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/cpufreq/omap-cpufreq.c:omap_target
```
**Symbols:**

```
c0bf36f4-c0bf3740: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09ed0)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:get_voltage
```
**Symbols:**

```
c000000000c09ed0-c000000000c09f38: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe00070133a)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:get_voltage
```
**Symbols:**

```
ffffffe00070133a-ffffffe000701382: dev_pm_opp_get_voltage (STB_GLOBAL)
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81863ea4)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81863ea4-ffffffff81863ebe: dev_pm_opp_get_voltage.cold (STB_LOCAL)
ffffffff81862080-ffffffff818620a8: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8182cb54)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff8182cb54-ffffffff8182cb6e: dev_pm_opp_get_voltage.cold (STB_LOCAL)
ffffffff8182ad30-ffffffff8182ad58: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818b4c34)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff818b4c34-ffffffff818b4c4e: dev_pm_opp_get_voltage.cold (STB_LOCAL)
ffffffff818b2e10-ffffffff818b2e38: dev_pm_opp_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818d0ee4)
Location: drivers/opp/core.c:101
Inline: True
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff818d0ee4-ffffffff818d0efe: dev_pm_opp_get_voltage.cold (STB_LOCAL)
ffffffff818cf0c0-ffffffff818cf0e8: dev_pm_opp_get_voltage (STB_GLOBAL)
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
