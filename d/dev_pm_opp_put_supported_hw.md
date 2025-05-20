# Function: <code>dev_pm_opp_put_supported_hw</code>

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
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d3f40)
Location: drivers/opp/core.c:1207
Inline: True
```
**Symbols:**

```
ffffffff817d3f40-ffffffff817d3fa4: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181ca20)
Location: drivers/opp/core.c:1214
Inline: False
```
**Symbols:**

```
ffffffff8181ca20-ffffffff8181ca6a: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848580)
Location: drivers/opp/core.c:1357
Inline: False
```
**Symbols:**

```
ffffffff81848580-ffffffff818485ca: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1428
Inline: False
```
**Symbols:**

```
ffffffff8188d537-ffffffff8188d54a: dev_pm_opp_put_supported_hw.cold (STB_LOCAL)
ffffffff8188b5c0-ffffffff8188b610: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bd6a0)
Location: drivers/opp/core.c:1477
Inline: False
```
**Symbols:**

```
ffffffff818bd6a0-ffffffff818bd6f0: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8198e210)
Location: drivers/opp/core.c:1584
Inline: False
```
**Symbols:**

```
ffffffff8198e210-ffffffff8198e279: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81991f40)
Location: drivers/opp/core.c:1668
Inline: False
```
**Symbols:**

```
ffffffff81991f40-ffffffff81991faf: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8197846d)
Location: drivers/opp/core.c:1844
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff819763c0-ffffffff8197641d: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81a213ed)
Location: drivers/opp/core.c:1854
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff81a1f160-ffffffff81a1f1bd: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8a36c)
Location: drivers/opp/core.c:1998
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff81b87bd0-ffffffff81b87c3d: dev_pm_opp_put_supported_hw (STB_GLOBAL)
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
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b183b8)
Location: drivers/opp/core.c:1477
Inline: False
```
**Symbols:**

```
ffff800010b183b8-ffff800010b1840c: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf336c)
Location: drivers/opp/core.c:1477
Inline: False
Direct callers:
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe
```
**Symbols:**

```
c0bf336c-c0bf33d0: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09a20)
Location: drivers/opp/core.c:1477
Inline: False
```
**Symbols:**

```
c000000000c09a20-c000000000c09a8c: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000700ff4)
Location: drivers/opp/core.c:1477
Inline: False
```
**Symbols:**

```
ffffffe000700ff4-ffffffe00070103e: dev_pm_opp_put_supported_hw (STB_GLOBAL)
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
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81861dc0)
Location: drivers/opp/core.c:1477
Inline: False
```
**Symbols:**

```
ffffffff81861dc0-ffffffff81861e10: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182aa70)
Location: drivers/opp/core.c:1477
Inline: False
```
**Symbols:**

```
ffffffff8182aa70-ffffffff8182aac0: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b2b50)
Location: drivers/opp/core.c:1477
Inline: False
```
**Symbols:**

```
ffffffff818b2b50-ffffffff818b2ba0: dev_pm_opp_put_supported_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_pm_opp_put_supported_hw(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cee00)
Location: drivers/opp/core.c:1477
Inline: False
```
**Symbols:**

```
ffffffff818cee00-ffffffff818cee50: dev_pm_opp_put_supported_hw (STB_GLOBAL)
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
