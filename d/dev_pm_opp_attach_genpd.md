# Function: <code>dev_pm_opp_attach_genpd</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1788
Inline: False
```
**Symbols:**

```
ffffffff8188d8e6-ffffffff8188d914: dev_pm_opp_attach_genpd.cold (STB_LOCAL)
ffffffff8188ce60-ffffffff8188cf25: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1841
Inline: False
```
**Symbols:**

```
ffffffff818bfa5b-ffffffff818bfac0: dev_pm_opp_attach_genpd.cold (STB_LOCAL)
ffffffff818bf000-ffffffff818bf161: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1955
Inline: False
```
**Symbols:**

```
ffffffff81991799-ffffffff819917f4: dev_pm_opp_attach_genpd.cold (STB_LOCAL)
ffffffff81990630-ffffffff819907ca: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2055
Inline: False
```
**Symbols:**

```
ffffffff81c29557-ffffffff81c295a5: dev_pm_opp_attach_genpd.cold (STB_LOCAL)
ffffffff81994550-ffffffff81994693: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2340
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81c1b64d-ffffffff81c1b69b: dev_pm_opp_attach_genpd.cold (STB_LOCAL)
ffffffff81978b10-ffffffff81978c55: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2350
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81d2b833-ffffffff81d2b881: dev_pm_opp_attach_genpd.cold (STB_LOCAL)
ffffffff81a21a90-ffffffff81a21bd5: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const const char * *names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2490
Inline: False
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81ef7a13-ffffffff81ef7a67: dev_pm_opp_attach_genpd.cold (STB_LOCAL)
ffffffff81b8aac0-ffffffff81b8ac18: dev_pm_opp_attach_genpd (STB_GLOBAL)
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
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1a238)
Location: drivers/opp/core.c:1841
Inline: False
```
**Symbols:**

```
ffff800010b1a238-ffff800010b1a3dc: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf4e8c)
Location: drivers/opp/core.c:1841
Inline: False
```
**Symbols:**

```
c0bf4e8c-c0bf5004: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0bea0)
Location: drivers/opp/core.c:1841
Inline: False
```
**Symbols:**

```
c000000000c0bea0-c000000000c0c0dc: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702a02)
Location: drivers/opp/core.c:1841
Inline: False
```
**Symbols:**

```
ffffffe000702a02-ffffffe000702b4c: dev_pm_opp_attach_genpd (STB_GLOBAL)
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
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1841
Inline: False
```
**Symbols:**

```
ffffffff8186417b-ffffffff818641e0: dev_pm_opp_attach_genpd.cold (STB_LOCAL)
ffffffff81863720-ffffffff81863881: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1841
Inline: False
```
**Symbols:**

```
ffffffff8182ce2b-ffffffff8182ce90: dev_pm_opp_attach_genpd.cold (STB_LOCAL)
ffffffff8182c3d0-ffffffff8182c531: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1841
Inline: False
```
**Symbols:**

```
ffffffff818b4f0b-ffffffff818b4f70: dev_pm_opp_attach_genpd.cold (STB_LOCAL)
ffffffff818b44b0-ffffffff818b4611: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct opp_table *dev_pm_opp_attach_genpd(struct device *dev, const char **names, struct device ***virt_devs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1841
Inline: False
```
**Symbols:**

```
ffffffff818d11bb-ffffffff818d1220: dev_pm_opp_attach_genpd.cold (STB_LOCAL)
ffffffff818d0760-ffffffff818d08c1: dev_pm_opp_attach_genpd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device ***virt_devs</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const char **names</code> ➡️ <code>const const char * *names</code>
</li>
</ul>
</details>
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
