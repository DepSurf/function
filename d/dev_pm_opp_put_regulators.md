# Function: <code>dev_pm_opp_put_regulators</code>

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
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d3dc0)
Location: drivers/opp/core.c:1414
Inline: False
```
**Symbols:**

```
ffffffff817d3dc0-ffffffff817d3e80: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181cbb0)
Location: drivers/opp/core.c:1398
Inline: False
```
**Symbols:**

```
ffffffff8181cbb0-ffffffff8181cc57: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848750)
Location: drivers/opp/core.c:1539
Inline: False
```
**Symbols:**

```
ffffffff81848750-ffffffff81848816: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1610
Inline: False
```
**Symbols:**

```
ffffffff8188d583-ffffffff8188d596: dev_pm_opp_put_regulators.cold (STB_LOCAL)
ffffffff8188b7c0-ffffffff8188b87b: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bd890)
Location: drivers/opp/core.c:1659
Inline: False
```
**Symbols:**

```
ffffffff818bd890-ffffffff818bd956: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8198e3c0)
Location: drivers/opp/core.c:1766
Inline: False
```
**Symbols:**

```
ffffffff8198e3c0-ffffffff8198e4e6: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff819920d0)
Location: drivers/opp/core.c:1856
Inline: False
```
**Symbols:**

```
ffffffff819920d0-ffffffff81992200: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81976700)
Location: drivers/opp/core.c:2033
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff81976700-ffffffff8197684e: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2043
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff81d2b208-ffffffff81d2b21c: dev_pm_opp_put_regulators.cold (STB_LOCAL)
ffffffff81a1f4b0-ffffffff81a1f608: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2186
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff81ef73f1-ffffffff81ef7405: dev_pm_opp_put_regulators.cold (STB_LOCAL)
ffffffff81b87fa0-ffffffff81b8810c: dev_pm_opp_put_regulators (STB_GLOBAL)
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
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18608)
Location: drivers/opp/core.c:1659
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_exit
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
```
**Symbols:**

```
ffff800010b18608-ffff800010b186b0: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf359c)
Location: drivers/opp/core.c:1659
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_exit
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_exit
```
**Symbols:**

```
c0bf359c-c0bf3640: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09cc0)
Location: drivers/opp/core.c:1659
Inline: False
```
**Symbols:**

```
c000000000c09cc0-c000000000c09da8: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe0007011c8)
Location: drivers/opp/core.c:1659
Inline: False
```
**Symbols:**

```
ffffffe0007011c8-ffffffe000701272: dev_pm_opp_put_regulators (STB_GLOBAL)
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
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81861fb0)
Location: drivers/opp/core.c:1659
Inline: False
```
**Symbols:**

```
ffffffff81861fb0-ffffffff81862076: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182ac60)
Location: drivers/opp/core.c:1659
Inline: False
```
**Symbols:**

```
ffffffff8182ac60-ffffffff8182ad26: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b2d40)
Location: drivers/opp/core.c:1659
Inline: False
```
**Symbols:**

```
ffffffff818b2d40-ffffffff818b2e06: dev_pm_opp_put_regulators (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_pm_opp_put_regulators(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818ceff0)
Location: drivers/opp/core.c:1659
Inline: False
```
**Symbols:**

```
ffffffff818ceff0-ffffffff818cf0b6: dev_pm_opp_put_regulators (STB_GLOBAL)
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
