# Function: <code>dev_pm_opp_is_turbo</code>

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
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d3f00)
Location: drivers/opp/core.c:161
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff817d3f00-ffffffff817d3f39: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181cce0)
Location: drivers/opp/core.c:159
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff8181cce0-ffffffff8181cd19: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818488a0)
Location: drivers/opp/core.c:143
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff818488a0-ffffffff818488d9: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8188d5e4)
Location: drivers/opp/core.c:158
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff8188d5e4-ffffffff8188d5fe: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff8188b910-ffffffff8188b940: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818bf7d2)
Location: drivers/opp/core.c:158
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff818bf7d2-ffffffff818bf7ec: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff818bd9f0-ffffffff818bda20: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81991252)
Location: drivers/opp/core.c:158
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff81991252-ffffffff8199126c: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff8198de80-ffffffff8198deb0: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81c28f5a)
Location: drivers/opp/core.c:158
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff81c28f5a-ffffffff81c28f74: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff81991870-ffffffff819918a0: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81c1b161)
Location: drivers/opp/core.c:188
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff81c1b161-ffffffff81c1b17c: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff81975e80-ffffffff81975eab: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:188
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff81d2b070-ffffffff81d2b0ba: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff81a1e990-ffffffff81a1e9ec: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81ef7333)
Location: drivers/opp/core.c:213
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff81ef7333-ffffffff81ef737d: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff81b87690-ffffffff81b876f2: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81d271e6)
Location: drivers/opp/core.c:257
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff820a89e8-ffffffff820a8a18: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff81d27190-ffffffff81d2720c: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81d903e6)
Location: drivers/opp/core.c:260
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff82129bd9-ffffffff82129c09: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff81d90390-ffffffff81d9040c: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81e47a46)
Location: drivers/opp/core.c:259
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff8220b922-ffffffff8220b952: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff81e479f0-ffffffff81e47a6c: dev_pm_opp_is_turbo (STB_GLOBAL)
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
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b187c8)
Location: drivers/opp/core.c:158
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffff800010b187c8-ffff800010b18824: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf37e8)
Location: drivers/opp/core.c:158
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
c0bf37e8-c0bf383c: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0a020)
Location: drivers/opp/core.c:158
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
c000000000c0a020-c000000000c0a090: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe00070141a)
Location: drivers/opp/core.c:158
Inline: True
```
**Symbols:**

```
ffffffe00070141a-ffffffe000701468: dev_pm_opp_is_turbo (STB_GLOBAL)
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
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81863ef2)
Location: drivers/opp/core.c:158
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff81863ef2-ffffffff81863f0c: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff81862110-ffffffff81862140: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8182cba2)
Location: drivers/opp/core.c:158
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff8182cba2-ffffffff8182cbbc: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff8182adc0-ffffffff8182adf0: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818b4c82)
Location: drivers/opp/core.c:158
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff818b4c82-ffffffff818b4c9c: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff818b2ea0-ffffffff818b2ed0: dev_pm_opp_is_turbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dev_pm_opp_is_turbo(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818d0f32)
Location: drivers/opp/core.c:158
Inline: True
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
```
**Symbols:**

```
ffffffff818d0f32-ffffffff818d0f4c: dev_pm_opp_is_turbo.cold (STB_LOCAL)
ffffffff818cf150-ffffffff818cf180: dev_pm_opp_is_turbo (STB_GLOBAL)
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
