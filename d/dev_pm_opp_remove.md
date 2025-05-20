# Function: <code>dev_pm_opp_remove</code>

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
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4d10)
Location: drivers/opp/core.c:934
Inline: False
```
**Symbols:**

```
ffffffff817d4d10-ffffffff817d4dad: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181d1b0)
Location: drivers/opp/core.c:941
Inline: False
```
**Symbols:**

```
ffffffff8181d1b0-ffffffff8181d258: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848ed0)
Location: drivers/opp/core.c:1046
Inline: False
```
**Symbols:**

```
ffffffff81848ed0-ffffffff81848f80: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188bdc0)
Location: drivers/opp/core.c:1120
Inline: False
```
**Symbols:**

```
ffffffff8188bdc0-ffffffff8188be61: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bdea0)
Location: drivers/opp/core.c:1169
Inline: False
```
**Symbols:**

```
ffffffff818bdea0-ffffffff818bdf41: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1232
Inline: False
```
**Symbols:**

```
ffffffff8199153b-ffffffff81991553: dev_pm_opp_remove.cold (STB_LOCAL)
ffffffff8198edc0-ffffffff8198ef36: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1295
Inline: False
```
**Symbols:**

```
ffffffff81c292fd-ffffffff81c29315: dev_pm_opp_remove.cold (STB_LOCAL)
ffffffff81992d90-ffffffff81992f06: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1452
Inline: False
```
**Symbols:**

```
ffffffff81c1b442-ffffffff81c1b45a: dev_pm_opp_remove.cold (STB_LOCAL)
ffffffff81977680-ffffffff819777f6: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1462
Inline: False
```
**Symbols:**

```
ffffffff81d2b519-ffffffff81d2b531: dev_pm_opp_remove.cold (STB_LOCAL)
ffffffff81a203d0-ffffffff81a20546: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1607
Inline: False
```
**Symbols:**

```
ffffffff81ef76b6-ffffffff81ef76ce: dev_pm_opp_remove.cold (STB_LOCAL)
ffffffff81b88e20-ffffffff81b88fa1: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d28940)
Location: drivers/opp/core.c:1579
Inline: False
```
**Symbols:**

```
ffffffff81d28940-ffffffff81d28b0d: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d91c60)
Location: drivers/opp/core.c:1587
Inline: False
```
**Symbols:**

```
ffffffff81d91c60-ffffffff81d91e25: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e49590)
Location: drivers/opp/core.c:1697
Inline: False
```
**Symbols:**

```
ffffffff81e49590-ffffffff81e49755: dev_pm_opp_remove (STB_GLOBAL)
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
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18c60)
Location: drivers/opp/core.c:1169
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_dvfs_device_opps_add
```
**Symbols:**

```
ffff800010b18c60-ffff800010b18d30: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3b04)
Location: drivers/opp/core.c:1169
Inline: False
Direct callers:
  - drivers/clk/tegra/cvb.c:tegra_cvb_remove_opp_table
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/firmware/arm_scmi/perf.c:scmi_dvfs_device_opps_add
```
**Symbols:**

```
c0bf3b04-c0bf3bb4: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0a570)
Location: drivers/opp/core.c:1169
Inline: False
```
**Symbols:**

```
c000000000c0a570-c000000000c0a684: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701770)
Location: drivers/opp/core.c:1169
Inline: False
```
**Symbols:**

```
ffffffe000701770-ffffffe00070182c: dev_pm_opp_remove (STB_GLOBAL)
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
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818625c0)
Location: drivers/opp/core.c:1169
Inline: False
```
**Symbols:**

```
ffffffff818625c0-ffffffff81862661: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182b270)
Location: drivers/opp/core.c:1169
Inline: False
```
**Symbols:**

```
ffffffff8182b270-ffffffff8182b311: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b3350)
Location: drivers/opp/core.c:1169
Inline: False
```
**Symbols:**

```
ffffffff818b3350-ffffffff818b33f1: dev_pm_opp_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_pm_opp_remove(struct device *dev, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cf600)
Location: drivers/opp/core.c:1169
Inline: False
```
**Symbols:**

```
ffffffff818cf600-ffffffff818cf6a1: dev_pm_opp_remove (STB_GLOBAL)
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
