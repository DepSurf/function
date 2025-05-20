# Function: <code>dev_pm_opp_of_remove_table</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: include/linux/pm_opp.h:329
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: include/linux/pm_opp.h:327
Inline: True
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
void dev_pm_opp_of_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffff800010b1b170)
Location: drivers/opp/of.c:518
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_del_provider
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
ffff800010b1b170-ffff800010b1b19c: dev_pm_opp_of_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_opp_of_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c0bf5b90)
Location: drivers/opp/of.c:518
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_del_provider
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_passive_exit
  - drivers/devfreq/exynos-bus.c:exynos_bus_exit
```
**Symbols:**

```
c0bf5b90-c0bf5bac: dev_pm_opp_of_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_of_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c000000000c0d380)
Location: drivers/opp/of.c:518
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_del_provider
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
c000000000c0d380-c000000000c0d3b4: dev_pm_opp_of_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_opp_of_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffffffe0007035a6)
Location: drivers/opp/of.c:518
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_del_provider
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
ffffffe0007035a6-ffffffe0007035d0: dev_pm_opp_of_remove_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
