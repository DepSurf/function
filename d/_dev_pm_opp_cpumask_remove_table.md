# Function: <code>_dev_pm_opp_cpumask_remove_table</code>

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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, bool of);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffff817d6030)
Location: drivers/opp/cpu.c:111
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff817d6030-ffffffff817d60b5: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, bool of);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:111
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff8181eda2-ffffffff8181edb8: _dev_pm_opp_cpumask_remove_table.cold.3 (STB_LOCAL)
ffffffff8181ed10-ffffffff8181ed86: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:111
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff8184ac45-ffffffff8184ac5b: _dev_pm_opp_cpumask_remove_table.cold.3 (STB_LOCAL)
ffffffff8184abb0-ffffffff8184ac26: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff8188dde1-ffffffff8188de0f: _dev_pm_opp_cpumask_remove_table.cold (STB_LOCAL)
ffffffff8188dd20-ffffffff8188dd8f: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff818bff81-ffffffff818bff9c: _dev_pm_opp_cpumask_remove_table.cold (STB_LOCAL)
ffffffff818bfeb0-ffffffff818bff23: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81991ce1-ffffffff81991cfc: _dev_pm_opp_cpumask_remove_table.cold (STB_LOCAL)
ffffffff81991c10-ffffffff81991c83: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81c29648-ffffffff81c29663: _dev_pm_opp_cpumask_remove_table.cold (STB_LOCAL)
ffffffff81994ef0-ffffffff81994f63: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81c1b9ef-ffffffff81c1ba0a: _dev_pm_opp_cpumask_remove_table.cold (STB_LOCAL)
ffffffff81979e30-ffffffff81979ea3: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81d2bcf9-ffffffff81d2bd14: _dev_pm_opp_cpumask_remove_table.cold (STB_LOCAL)
ffffffff81a22e40-ffffffff81a22eb3: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81ef7f0f-ffffffff81ef7f29: _dev_pm_opp_cpumask_remove_table.cold (STB_LOCAL)
ffffffff81b8bf60-ffffffff81b8bfdb: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffff81d2b7f0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81d2b7f0-ffffffff81d2b88a: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffff81d94aa0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81d94aa0-ffffffff81d94b3a: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffff81e4c5b0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81e4c5b0-ffffffff81e4c64a: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffff800010b1af70)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_cpumask_remove_table
```
**Symbols:**

```
ffff800010b1af70-ffff800010b1b02c: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (c0bf59b0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_cpumask_remove_table
```
**Symbols:**

```
c0bf59b0-c0bf5a54: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (c000000000c0d040)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_cpumask_remove_table
```
**Symbols:**

```
c000000000c0d040-c000000000c0d140: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/cpu.c (ffffffe000703362)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_cpumask_remove_table
```
**Symbols:**

```
ffffffe000703362-ffffffe0007033fc: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff818646a1-ffffffff818646bc: _dev_pm_opp_cpumask_remove_table.cold (STB_LOCAL)
ffffffff818645d0-ffffffff81864643: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff8182d351-ffffffff8182d36c: _dev_pm_opp_cpumask_remove_table.cold (STB_LOCAL)
ffffffff8182d280-ffffffff8182d2f3: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff818b5431-ffffffff818b544c: _dev_pm_opp_cpumask_remove_table.cold (STB_LOCAL)
ffffffff818b5360-ffffffff818b53d3: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask *cpumask, int last_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/cpu.c (0)
Location: drivers/opp/cpu.c:108
Inline: False
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff818d16e1-ffffffff818d16fc: _dev_pm_opp_cpumask_remove_table.cold (STB_LOCAL)
ffffffff818d1610-ffffffff818d1683: _dev_pm_opp_cpumask_remove_table (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int last_cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>bool of</code>
</li>
</ul>
</details>
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
