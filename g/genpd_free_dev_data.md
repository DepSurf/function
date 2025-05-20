# Function: <code>genpd_free_dev_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815b09a0)
Location: drivers/base/power/domain.c:1044
Inline: False
Direct callers:
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
**Symbols:**

```
ffffffff815b09a0-ffffffff815b0a01: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815dfc60)
Location: drivers/base/power/domain.c:1154
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
**Symbols:**

```
ffffffff815dfc60-ffffffff815dfcc1: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f4b10)
Location: drivers/base/power/domain.c:1235
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
**Symbols:**

```
ffffffff815f4b10-ffffffff815f4b6b: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165ca00)
Location: drivers/base/power/domain.c:1358
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
**Symbols:**

```
ffffffff8165ca00-ffffffff8165ca5b: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81698750)
Location: drivers/base/power/domain.c:1363
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff81698750-ffffffff816987ab: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b8fa0)
Location: drivers/base/power/domain.c:1442
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff816b8fa0-ffffffff816b8ffb: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816f2fc0)
Location: drivers/base/power/domain.c:1441
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff816f2fc0-ffffffff816f301d: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81717490)
Location: drivers/base/power/domain.c:1436
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff81717490-ffffffff817174ed: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d26f7)
Location: drivers/base/power/domain.c:1425
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e6e37)
Location: drivers/base/power/domain.c:1490
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817cb647)
Location: drivers/base/power/domain.c:1486
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81855667)
Location: drivers/base/power/domain.c:1526
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199b8dc)
Location: drivers/base/power/domain.c:1558
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0cabc)
Location: drivers/base/power/domain.c:1537
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5aabc)
Location: drivers/base/power/domain.c:1563
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa257c)
Location: drivers/pmdomain/core.c:1570
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_remove_device
  - drivers/pmdomain/core.c:genpd_add_device
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
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff8000109098a0)
Location: drivers/base/power/domain.c:1436
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
ffff8000109098a0-ffff80001090994c: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09efe20)
Location: drivers/base/power/domain.c:1436
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
c09efe20-c09efe80: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a8f70)
Location: drivers/base/power/domain.c:1436
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
c0000000009a8f70-c0000000009a902c: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058fa00)
Location: drivers/base/power/domain.c:1436
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
ffffffe00058fa00-ffffffe00058fa92: genpd_free_dev_data (STB_LOCAL)
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
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816dd7c0)
Location: drivers/base/power/domain.c:1436
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff816dd7c0-ffffffff816dd81d: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b7e30)
Location: drivers/base/power/domain.c:1436
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff816b7e30-ffffffff816b7e87: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8170b150)
Location: drivers/base/power/domain.c:1436
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff8170b150-ffffffff8170b1ad: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void genpd_free_dev_data(struct device *dev, struct generic_pm_domain_data *gpd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81723350)
Location: drivers/base/power/domain.c:1436
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff81723350-ffffffff817233a4: genpd_free_dev_data (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
