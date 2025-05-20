# Function: <code>dev_pm_opp_remove_table</code>

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
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d5cf0)
Location: drivers/opp/core.c:1969
Inline: False
Direct callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff817d5cf0-ffffffff817d5d05: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181e9b0)
Location: drivers/opp/core.c:1860
Inline: False
Direct callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff8181e9b0-ffffffff8181e9c5: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8184a810)
Location: drivers/opp/core.c:2060
Inline: False
```
**Symbols:**

```
ffffffff8184a810-ffffffff8184a820: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188d480)
Location: drivers/opp/core.c:2177
Inline: False
```
**Symbols:**

```
ffffffff8188d480-ffffffff8188d490: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bf6e0)
Location: drivers/opp/core.c:2226
Inline: False
```
**Symbols:**

```
ffffffff818bf6e0-ffffffff818bf6f0: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81991160)
Location: drivers/opp/core.c:2411
Inline: False
```
**Symbols:**

```
ffffffff81991160-ffffffff81991170: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2481
Inline: False
Direct callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81c292b5-ffffffff81c292fd: dev_pm_opp_remove_table.cold (STB_LOCAL)
ffffffff81992c70-ffffffff81992d81: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2855
Inline: False
Direct callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81c1b3fa-ffffffff81c1b442: dev_pm_opp_remove_table.cold (STB_LOCAL)
ffffffff81977560-ffffffff81977671: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2865
Inline: False
Direct callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81d2b407-ffffffff81d2b44f: dev_pm_opp_remove_table.cold (STB_LOCAL)
ffffffff81a1feb0-ffffffff81a1ffc1: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:3005
Inline: False
Direct callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81ef75db-ffffffff81ef75ff: dev_pm_opp_remove_table.cold (STB_LOCAL)
ffffffff81b88a70-ffffffff81b88b7e: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d287f0)
Location: drivers/opp/core.c:3012
Inline: False
Direct callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81d287f0-ffffffff81d28921: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d91990)
Location: drivers/opp/core.c:3026
Inline: False
Direct callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81d91990-ffffffff81d91ac2: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e492c0)
Location: drivers/opp/core.c:3151
Inline: False
Direct callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81e492c0-ffffffff81e493f2: dev_pm_opp_remove_table (STB_GLOBAL)
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
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1ab28)
Location: drivers/opp/core.c:2226
Inline: False
```
**Symbols:**

```
ffff800010b1ab28-ffff800010b1ab54: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf5650)
Location: drivers/opp/core.c:2226
Inline: False
```
**Symbols:**

```
c0bf5650-c0bf566c: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0ca60)
Location: drivers/opp/core.c:2226
Inline: False
```
**Symbols:**

```
c000000000c0ca60-c000000000c0ca74: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000703144)
Location: drivers/opp/core.c:2226
Inline: False
```
**Symbols:**

```
ffffffe000703144-ffffffe00070316e: dev_pm_opp_remove_table (STB_GLOBAL)
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
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81863e00)
Location: drivers/opp/core.c:2226
Inline: False
```
**Symbols:**

```
ffffffff81863e00-ffffffff81863e10: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182cab0)
Location: drivers/opp/core.c:2226
Inline: False
```
**Symbols:**

```
ffffffff8182cab0-ffffffff8182cac0: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b4b90)
Location: drivers/opp/core.c:2226
Inline: False
```
**Symbols:**

```
ffffffff818b4b90-ffffffff818b4ba0: dev_pm_opp_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_pm_opp_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818d0e40)
Location: drivers/opp/core.c:2226
Inline: False
```
**Symbols:**

```
ffffffff818d0e40-ffffffff818d0e50: dev_pm_opp_remove_table (STB_GLOBAL)
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
