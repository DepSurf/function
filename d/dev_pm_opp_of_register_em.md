# Function: <code>dev_pm_opp_of_register_em</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/pm_opp.h:426
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/pm_opp.h:506
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/pm_opp.h:506
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/pm_opp.h:547
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/pm_opp.h:468
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/pm_opp.h:468
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/pm_opp.h:514
Inline: True
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
void dev_pm_opp_of_register_em(struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffff800010b1b270)
Location: drivers/opp/of.c:1103
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
```
**Symbols:**

```
ffff800010b1b270-ffff800010b1b314: dev_pm_opp_of_register_em (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_opp_of_register_em(struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c0bf5e04)
Location: drivers/opp/of.c:1103
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/cpufreq/omap-cpufreq.c:omap_cpu_init
```
**Symbols:**

```
c0bf5e04-c0bf5ea8: dev_pm_opp_of_register_em (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_of_register_em(struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c000000000c0d7c0)
Location: drivers/opp/of.c:1103
Inline: False
```
**Symbols:**

```
c000000000c0d7c0-c000000000c0d88c: dev_pm_opp_of_register_em (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_opp_of_register_em(struct cpumask *cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffffffe000703844)
Location: drivers/opp/of.c:1103
Inline: False
```
**Symbols:**

```
ffffffe000703844-ffffffe0007038be: dev_pm_opp_of_register_em (STB_GLOBAL)
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
