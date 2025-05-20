# Function: <code>dev_pm_opp_set_sharing_cpus</code>

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
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffff817d5d10)
Location: drivers/opp/cpu.c:157
Inline: False
```
**Symbols:**

```
ffffffff817d5d10-ffffffff817d5dd3: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffff8181ea10)
Location: drivers/opp/cpu.c:157
Inline: False
```
**Symbols:**

```
ffffffff8181ea10-ffffffff8181ead3: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffff8184a890)
Location: drivers/opp/cpu.c:158
Inline: False
```
**Symbols:**

```
ffffffff8184a890-ffffffff8184a953: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff8188dda5-ffffffff8188dde1: dev_pm_opp_set_sharing_cpus.cold (STB_LOCAL)
ffffffff8188da20-ffffffff8188dab7: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff818bff45-ffffffff818bff81: dev_pm_opp_set_sharing_cpus.cold (STB_LOCAL)
ffffffff818bfbb0-ffffffff818bfc47: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff81991ca5-ffffffff81991ce1: dev_pm_opp_set_sharing_cpus.cold (STB_LOCAL)
ffffffff81991910-ffffffff819919a7: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff81c2960c-ffffffff81c29648: dev_pm_opp_set_sharing_cpus.cold (STB_LOCAL)
ffffffff81994bf0-ffffffff81994c87: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff81c1b9b3-ffffffff81c1b9ef: dev_pm_opp_set_sharing_cpus.cold (STB_LOCAL)
ffffffff81979b30-ffffffff81979bc7: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff81d2bcbd-ffffffff81d2bcf9: dev_pm_opp_set_sharing_cpus.cold (STB_LOCAL)
ffffffff81a22b40-ffffffff81a22bd7: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff81ef7ed5-ffffffff81ef7f0f: dev_pm_opp_set_sharing_cpus.cold (STB_LOCAL)
ffffffff81b8bc40-ffffffff81b8bce0: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffff81d2b6e0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff81d2b6e0-ffffffff81d2b7db: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffff81d949a0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff81d949a0-ffffffff81d94a84: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffff81e4c4b0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff81e4c4b0-ffffffff81e4c594: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
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
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffff800010b1ab78)
Location: drivers/opp/cpu.c:155
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
```
**Symbols:**

```
ffff800010b1ab78-ffff800010b1ac94: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (c0bf566c)
Location: drivers/opp/cpu.c:155
Inline: False
Direct callers:
  - arch/arm/mach-vexpress/spc.c:ve_spc_clk_init
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
```
**Symbols:**

```
c0bf566c-c0bf575c: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (c000000000c0ca80)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
c000000000c0ca80-c000000000c0cc28: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffe00070316e)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffe00070316e-ffffffe000703260: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
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
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff81864665-ffffffff818646a1: dev_pm_opp_set_sharing_cpus.cold (STB_LOCAL)
ffffffff818642d0-ffffffff81864367: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff8182d315-ffffffff8182d351: dev_pm_opp_set_sharing_cpus.cold (STB_LOCAL)
ffffffff8182cf80-ffffffff8182d017: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff818b53f5-ffffffff818b5431: dev_pm_opp_set_sharing_cpus.cold (STB_LOCAL)
ffffffff818b5060-ffffffff818b50f7: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_sharing_cpus(struct device *cpu_dev, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:155
Inline: False
```
**Symbols:**

```
ffffffff818d16a5-ffffffff818d16e1: dev_pm_opp_set_sharing_cpus.cold (STB_LOCAL)
ffffffff818d1310-ffffffff818d13a7: dev_pm_opp_set_sharing_cpus (STB_GLOBAL)
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
