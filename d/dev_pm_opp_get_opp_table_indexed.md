# Function: <code>dev_pm_opp_get_opp_table_indexed</code>

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
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8184a0e0)
Location: drivers/opp/core.c:914
Inline: False
```
**Symbols:**

```
ffffffff8184a0e0-ffffffff8184a0f0: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188cf50)
Location: drivers/opp/core.c:988
Inline: False
```
**Symbols:**

```
ffffffff8188cf50-ffffffff8188cf60: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bf190)
Location: drivers/opp/core.c:1037
Inline: False
```
**Symbols:**

```
ffffffff818bf190-ffffffff818bf1a0: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81990820)
Location: drivers/opp/core.c:1120
Inline: False
```
**Symbols:**

```
ffffffff81990820-ffffffff81990871: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1a410)
Location: drivers/opp/core.c:1037
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
**Symbols:**

```
ffff800010b1a410-ffff800010b1a444: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf5024)
Location: drivers/opp/core.c:1037
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
**Symbols:**

```
c0bf5024-c0bf5040: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0c100)
Location: drivers/opp/core.c:1037
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
**Symbols:**

```
c000000000c0c100-c000000000c0c114: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702b76)
Location: drivers/opp/core.c:1037
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
**Symbols:**

```
ffffffe000702b76-ffffffe000702ba8: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
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
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818638b0)
Location: drivers/opp/core.c:1037
Inline: False
```
**Symbols:**

```
ffffffff818638b0-ffffffff818638c0: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182c560)
Location: drivers/opp/core.c:1037
Inline: False
```
**Symbols:**

```
ffffffff8182c560-ffffffff8182c570: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b4640)
Location: drivers/opp/core.c:1037
Inline: False
```
**Symbols:**

```
ffffffff818b4640-ffffffff818b4650: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct opp_table *dev_pm_opp_get_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818d08f0)
Location: drivers/opp/core.c:1037
Inline: False
```
**Symbols:**

```
ffffffff818d08f0-ffffffff818d0900: dev_pm_opp_get_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
