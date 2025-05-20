# Function: <code>dev_pm_opp_set_regulators</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d52f0)
Location: drivers/opp/core.c:1340
Inline: False
```
**Symbols:**

```
ffffffff817d52f0-ffffffff817d54d6: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181e060)
Location: drivers/opp/core.c:1326
Inline: False
```
**Symbols:**

```
ffffffff8181e060-ffffffff8181e222: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81849d90)
Location: drivers/opp/core.c:1469
Inline: False
```
**Symbols:**

```
ffffffff81849d90-ffffffff81849f88: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1540
Inline: False
```
**Symbols:**

```
ffffffff8188d839-ffffffff8188d88e: dev_pm_opp_set_regulators.cold (STB_LOCAL)
ffffffff8188cb70-ffffffff8188cd3d: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1589
Inline: False
```
**Symbols:**

```
ffffffff818bfa15-ffffffff818bfa3e: dev_pm_opp_set_regulators.cold (STB_LOCAL)
ffffffff818becf0-ffffffff818beed6: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1696
Inline: False
```
**Symbols:**

```
ffffffff81991753-ffffffff8199177c: dev_pm_opp_set_regulators.cold (STB_LOCAL)
ffffffff81990000-ffffffff81990223: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1786
Inline: False
```
**Symbols:**

```
ffffffff81c29511-ffffffff81c2953a: dev_pm_opp_set_regulators.cold (STB_LOCAL)
ffffffff81994210-ffffffff819943ef: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1953
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff81c1b611-ffffffff81c1b632: dev_pm_opp_set_regulators.cold (STB_LOCAL)
ffffffff81978560-ffffffff81978768: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1963
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff81d2b7f7-ffffffff81d2b818: dev_pm_opp_set_regulators.cold (STB_LOCAL)
ffffffff81a214e0-ffffffff81a216e8: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8a480)
Location: drivers/opp/core.c:2107
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff81b8a480-ffffffff81b8a6a3: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b19eb8)
Location: drivers/opp/core.c:1589
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
```
**Symbols:**

```
ffff800010b19eb8-ffff800010b1a0ac: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf4b4c)
Location: drivers/opp/core.c:1589
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
```
**Symbols:**

```
c0bf4b4c-c0bf4d3c: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0ba50)
Location: drivers/opp/core.c:1589
Inline: False
```
**Symbols:**

```
c000000000c0ba50-c000000000c0bd28: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702730)
Location: drivers/opp/core.c:1589
Inline: False
```
**Symbols:**

```
ffffffe000702730-ffffffe0007028bc: dev_pm_opp_set_regulators (STB_GLOBAL)
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
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1589
Inline: False
```
**Symbols:**

```
ffffffff81864135-ffffffff8186415e: dev_pm_opp_set_regulators.cold (STB_LOCAL)
ffffffff81863410-ffffffff818635f6: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1589
Inline: False
```
**Symbols:**

```
ffffffff8182cde5-ffffffff8182ce0e: dev_pm_opp_set_regulators.cold (STB_LOCAL)
ffffffff8182c0c0-ffffffff8182c2a6: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1589
Inline: False
```
**Symbols:**

```
ffffffff818b4ec5-ffffffff818b4eee: dev_pm_opp_set_regulators.cold (STB_LOCAL)
ffffffff818b41a0-ffffffff818b4386: dev_pm_opp_set_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_regulators(struct device *dev, const const char * *names, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1589
Inline: False
```
**Symbols:**

```
ffffffff818d1175-ffffffff818d119e: dev_pm_opp_set_regulators.cold (STB_LOCAL)
ffffffff818d0450-ffffffff818d0636: dev_pm_opp_set_regulators (STB_GLOBAL)
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
