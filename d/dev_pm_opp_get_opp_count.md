# Function: <code>dev_pm_opp_get_opp_count</code>

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
In drivers/devfreq/devfreq.c (0)
Location: include/linux/pm_opp.h:88
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
Location: include/linux/pm_opp.h:142
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
Location: include/linux/pm_opp.h:156
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d44a0)
Location: drivers/opp/core.c:312
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff817d44a0-ffffffff817d4533: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181dd00)
Location: drivers/opp/core.c:327
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff8181dd00-ffffffff8181dd75: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818499f0)
Location: drivers/opp/core.c:311
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff818499f0-ffffffff81849a6a: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188c7d0)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8188c7d0-ffffffff8188c83c: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818be940)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818be940-ffffffff818be9ac: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:set_freq_table
```
**Symbols:**

```
ffffffff81991462-ffffffff81991481: dev_pm_opp_get_opp_count.cold (STB_LOCAL)
ffffffff8198e990-ffffffff8198ea71: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:set_freq_table
```
**Symbols:**

```
ffffffff81c291dc-ffffffff81c291fb: dev_pm_opp_get_opp_count.cold (STB_LOCAL)
ffffffff81992840-ffffffff81992921: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:356
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81c1b2d3-ffffffff81c1b2f2: dev_pm_opp_get_opp_count.cold (STB_LOCAL)
ffffffff81976eb0-ffffffff81976f91: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:356
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81d2b391-ffffffff81d2b3cc: dev_pm_opp_get_opp_count.cold (STB_LOCAL)
ffffffff81a1fca0-ffffffff81a1fda8: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:381
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81ef7565-ffffffff81ef75a0: dev_pm_opp_get_opp_count.cold (STB_LOCAL)
ffffffff81b88840-ffffffff81b88956: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:425
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff820a8ae1-ffffffff820a8afd: dev_pm_opp_get_opp_count.cold (STB_LOCAL)
ffffffff81d286b0-ffffffff81d287df: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:428
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff82129cb7-ffffffff82129cd3: dev_pm_opp_get_opp_count.cold (STB_LOCAL)
ffffffff81d91850-ffffffff81d9197f: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:427
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8220ba00-ffffffff8220ba1c: dev_pm_opp_get_opp_count.cold (STB_LOCAL)
ffffffff81e49180-ffffffff81e492af: dev_pm_opp_get_opp_count (STB_GLOBAL)
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
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b19a80)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffff800010b19a80-ffff800010b19b10: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf4758)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
c0bf4758-c0bf47dc: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0b520)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
c000000000c0b520-c000000000c0b5cc: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe00070235c)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffe00070235c-ffffffe0007023e4: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81863060)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81863060-ffffffff818630cc: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182bd10)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8182bd10-ffffffff8182bd7c: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b3df0)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818b3df0-ffffffff818b3e5c: dev_pm_opp_get_opp_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818d00a0)
Location: drivers/opp/core.c:326
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818d00a0-ffffffff818d010c: dev_pm_opp_get_opp_count (STB_GLOBAL)
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
