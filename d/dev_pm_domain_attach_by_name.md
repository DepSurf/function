# Function: <code>dev_pm_domain_attach_by_name</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816aca90)
Location: drivers/base/power/common.c:162
Inline: False
```
**Symbols:**

```
ffffffff816aca90-ffffffff816acab0: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816e6540)
Location: drivers/base/power/common.c:160
Inline: False
```
**Symbols:**

```
ffffffff816e6540-ffffffff816e6560: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff8170a910)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff8170a910-ffffffff8170a930: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817c58f0)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff817c58f0-ffffffff817c5910: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817da400)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff817da400-ffffffff817da420: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817be7c0)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff817be7c0-ffffffff817be7e0: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81848b40)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81848b40-ffffffff81848b60: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff8198d9e0)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff8198d9e0-ffffffff8198da02: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81afd8b0)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
**Symbols:**

```
ffffffff81afd8b0-ffffffff81afd8d2: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81b4bca0)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
**Symbols:**

```
ffffffff81b4bca0-ffffffff81b4bcc2: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81ba4090)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
**Symbols:**

```
ffffffff81ba4090-ffffffff81ba40b2: dev_pm_domain_attach_by_name (STB_GLOBAL)
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
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffff8000108f91d8)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffff8000108f91d8-ffff8000108f9224: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (c09e4b8c)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
c09e4b8c-c09e4bbc: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (c000000000995360)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
c000000000995360-c0000000009953b4: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffe000588d64)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffe000588d64-ffffffe000588daa: dev_pm_domain_attach_by_name (STB_GLOBAL)
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
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816d0060)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff816d0060-ffffffff816d0080: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816ab390)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff816ab390-ffffffff816ab3b0: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816fe5d0)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff816fe5d0-ffffffff816fe5f0: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *dev_pm_domain_attach_by_name(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81718e20)
Location: drivers/base/power/common.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81718e20-ffffffff81718e40: dev_pm_domain_attach_by_name (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *name</code> ➡️ <code>const char *name</code>
</li>
</ul>
</details>
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
