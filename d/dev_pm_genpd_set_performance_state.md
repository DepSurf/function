# Function: <code>dev_pm_genpd_set_performance_state</code>

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
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165a290)
Location: drivers/base/power/domain.c:256
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff8165a290-ffffffff8165a3c6: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81695d90)
Location: drivers/base/power/domain.c:257
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81695d90-ffffffff81695ee4: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b7e70)
Location: drivers/base/power/domain.c:378
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_genpd_virt_dev
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff816b7e70-ffffffff816b7f7f: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:381
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff816f354a-ffffffff816f3563: dev_pm_genpd_set_performance_state.cold (STB_LOCAL)
ffffffff816f1ac0-ffffffff816f1bd7: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81716220)
Location: drivers/base/power/domain.c:376
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff81716220-ffffffff81716351: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d22e0)
Location: drivers/base/power/domain.c:376
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff817d22e0-ffffffff817d244f: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e6af0)
Location: drivers/base/power/domain.c:391
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:_set_required_opp
```
**Symbols:**

```
ffffffff817e6af0-ffffffff817e6c5f: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817caef0)
Location: drivers/base/power/domain.c:397
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:_set_required_opp
```
**Symbols:**

```
ffffffff817caef0-ffffffff817cb03c: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81855080)
Location: drivers/base/power/domain.c:435
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:_set_required_opp
```
**Symbols:**

```
ffffffff81855080-ffffffff8185518e: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199bd00)
Location: drivers/base/power/domain.c:440
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:_set_required_opp
```
**Symbols:**

```
ffffffff8199bd00-ffffffff8199be56: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0cf20)
Location: drivers/base/power/domain.c:437
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:_set_required_opp
```
**Symbols:**

```
ffffffff81b0cf20-ffffffff81b0d076: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5af20)
Location: drivers/base/power/domain.c:437
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_performance_state
```
**Symbols:**

```
ffffffff81b5af20-ffffffff81b5b072: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa2d20)
Location: drivers/pmdomain/core.c:455
Inline: False
```
**Symbols:**

```
ffffffff81aa2d20-ffffffff81aa2dc3: dev_pm_genpd_set_performance_state (STB_GLOBAL)
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
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010907400)
Location: drivers/base/power/domain.c:376
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffff800010907400-ffff800010907548: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f1104)
Location: drivers/base/power/domain.c:376
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
c09f1104-c09f122c: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a6b20)
Location: drivers/base/power/domain.c:376
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
c0000000009a6b20-c0000000009a6d00: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058e91a)
Location: drivers/base/power/domain.c:376
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffe00058e91a-ffffffe00058e9f6: dev_pm_genpd_set_performance_state (STB_GLOBAL)
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
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816dc550)
Location: drivers/base/power/domain.c:376
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff816dc550-ffffffff816dc681: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b6bd0)
Location: drivers/base/power/domain.c:376
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff816b6bd0-ffffffff816b6d01: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81709ee0)
Location: drivers/base/power/domain.c:376
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff81709ee0-ffffffff8170a011: dev_pm_genpd_set_performance_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device *dev, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81724a50)
Location: drivers/base/power/domain.c:376
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff81724a50-ffffffff81724b81: dev_pm_genpd_set_performance_state (STB_GLOBAL)
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
