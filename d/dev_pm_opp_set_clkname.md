# Function: <code>dev_pm_opp_set_clkname</code>

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
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d54e0)
Location: drivers/opp/core.c:1451
Inline: False
```
**Symbols:**

```
ffffffff817d54e0-ffffffff817d5590: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181e230)
Location: drivers/opp/core.c:1434
Inline: False
```
**Symbols:**

```
ffffffff8181e230-ffffffff8181e2ef: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81849f90)
Location: drivers/opp/core.c:1575
Inline: False
```
**Symbols:**

```
ffffffff81849f90-ffffffff8184a04f: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1646
Inline: False
```
**Symbols:**

```
ffffffff8188d88e-ffffffff8188d8c4: dev_pm_opp_set_clkname.cold (STB_LOCAL)
ffffffff8188cd40-ffffffff8188cde6: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1695
Inline: False
```
**Symbols:**

```
ffffffff818bfa3e-ffffffff818bfa5b: dev_pm_opp_set_clkname.cold (STB_LOCAL)
ffffffff818beee0-ffffffff818bef8d: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1809
Inline: False
```
**Symbols:**

```
ffffffff8199177c-ffffffff81991799: dev_pm_opp_set_clkname.cold (STB_LOCAL)
ffffffff81990460-ffffffff81990555: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1900
Inline: False
```
**Symbols:**

```
ffffffff81c2953a-ffffffff81c29557: dev_pm_opp_set_clkname.cold (STB_LOCAL)
ffffffff819943f0-ffffffff819944a6: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2112
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff81c1b632-ffffffff81c1b64d: dev_pm_opp_set_clkname.cold (STB_LOCAL)
ffffffff819787d0-ffffffff8197888a: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2122
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff81d2b818-ffffffff81d2b833: dev_pm_opp_set_clkname.cold (STB_LOCAL)
ffffffff81a21750-ffffffff81a2180a: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8a720)
Location: drivers/opp/core.c:2265
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff81b8a720-ffffffff81b8a7f8: dev_pm_opp_set_clkname (STB_GLOBAL)
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
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1a0b0)
Location: drivers/opp/core.c:1695
Inline: False
```
**Symbols:**

```
ffff800010b1a0b0-ffff800010b1a19c: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf4d3c)
Location: drivers/opp/core.c:1695
Inline: False
```
**Symbols:**

```
c0bf4d3c-c0bf4e0c: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0bd30)
Location: drivers/opp/core.c:1695
Inline: False
```
**Symbols:**

```
c000000000c0bd30-c000000000c0bdc4: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe0007028bc)
Location: drivers/opp/core.c:1695
Inline: False
```
**Symbols:**

```
ffffffe0007028bc-ffffffe000702986: dev_pm_opp_set_clkname (STB_GLOBAL)
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
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1695
Inline: False
```
**Symbols:**

```
ffffffff8186415e-ffffffff8186417b: dev_pm_opp_set_clkname.cold (STB_LOCAL)
ffffffff81863600-ffffffff818636ad: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1695
Inline: False
```
**Symbols:**

```
ffffffff8182ce0e-ffffffff8182ce2b: dev_pm_opp_set_clkname.cold (STB_LOCAL)
ffffffff8182c2b0-ffffffff8182c35d: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1695
Inline: False
```
**Symbols:**

```
ffffffff818b4eee-ffffffff818b4f0b: dev_pm_opp_set_clkname.cold (STB_LOCAL)
ffffffff818b4390-ffffffff818b443d: dev_pm_opp_set_clkname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_set_clkname(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1695
Inline: False
```
**Symbols:**

```
ffffffff818d119e-ffffffff818d11bb: dev_pm_opp_set_clkname.cold (STB_LOCAL)
ffffffff818d0640-ffffffff818d06ed: dev_pm_opp_set_clkname (STB_GLOBAL)
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
