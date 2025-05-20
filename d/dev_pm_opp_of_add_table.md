# Function: <code>dev_pm_opp_of_add_table</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
int dev_pm_opp_of_add_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffff800010b1c4b8)
Location: drivers/opp/of.c:775
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
ffff800010b1c4b8-ffff800010b1c660: dev_pm_opp_of_add_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_pm_opp_of_add_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c0bf6d10)
Location: drivers/opp/of.c:775
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
```
**Symbols:**

```
c0bf6d10-c0bf6e88: dev_pm_opp_of_add_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_pm_opp_of_add_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c000000000c0ec50)
Location: drivers/opp/of.c:775
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
c000000000c0ec50-c000000000c0ee8c: dev_pm_opp_of_add_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_pm_opp_of_add_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffffffe000704558)
Location: drivers/opp/of.c:775
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
ffffffe000704558-ffffffe0007046ea: dev_pm_opp_of_add_table (STB_GLOBAL)
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
