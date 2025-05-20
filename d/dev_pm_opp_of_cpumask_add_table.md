# Function: <code>dev_pm_opp_of_cpumask_add_table</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_opp_of_cpumask_add_table(const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffff800010b1c660)
Location: drivers/opp/of.c:868
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
```
**Symbols:**

```
ffff800010b1c660-ffff800010b1c780: dev_pm_opp_of_cpumask_add_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_opp_of_cpumask_add_table(const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c0bf6e88)
Location: drivers/opp/of.c:868
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
```
**Symbols:**

```
c0bf6e88-c0bf6f94: dev_pm_opp_of_cpumask_add_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_opp_of_cpumask_add_table(const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c000000000c0ee90)
Location: drivers/opp/of.c:868
Inline: True
```
**Symbols:**

```
c000000000c0ee90-c000000000c0f008: dev_pm_opp_of_cpumask_add_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_opp_of_cpumask_add_table(const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffffffe0007046ea)
Location: drivers/opp/of.c:868
Inline: True
```
**Symbols:**

```
ffffffe0007046ea-ffffffe0007047c2: dev_pm_opp_of_cpumask_add_table (STB_GLOBAL)
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
