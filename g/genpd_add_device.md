# Function: <code>genpd_add_device</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815dfeb7)
Location: drivers/base/power/domain.c:1169
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f4d67)
Location: drivers/base/power/domain.c:1248
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165cc67)
Location: drivers/base/power/domain.c:1371
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816989a2)
Location: drivers/base/power/domain.c:1376
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b91f2)
Location: drivers/base/power/domain.c:1455
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816f3243)
Location: drivers/base/power/domain.c:1503
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817176a3)
Location: drivers/base/power/domain.c:1498
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d2900)
Location: drivers/base/power/domain.c:1487
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff817d2900-ffffffff817d2b07: genpd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e7040)
Location: drivers/base/power/domain.c:1552
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff817e7040-ffffffff817e7247: genpd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817cc100)
Location: drivers/base/power/domain.c:1548
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff817cc100-ffffffff817cc3c2: genpd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff818567d0)
Location: drivers/base/power/domain.c:1588
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff818567d0-ffffffff81856a92: genpd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199b470)
Location: drivers/base/power/domain.c:1621
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff8199b470-ffffffff8199b7ba: genpd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0c630)
Location: drivers/base/power/domain.c:1600
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff81b0c630-ffffffff81b0c97e: genpd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5a670)
Location: drivers/base/power/domain.c:1626
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff81b5a670-ffffffff81b5a966: genpd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa20d0)
Location: drivers/pmdomain/core.c:1633
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff81aa20d0-ffffffff81aa2424: genpd_add_device (STB_LOCAL)
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
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010909f70)
Location: drivers/base/power/domain.c:1498
Inline: False
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffff800010909f70-ffff80001090a26c: genpd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f1460)
Location: drivers/base/power/domain.c:1498
Inline: False
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
c09f1460-c09f16ec: genpd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009aa1b0)
Location: drivers/base/power/domain.c:1498
Inline: False
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
c0000000009aa1b0-c0000000009aa5b8: genpd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int genpd_add_device(struct generic_pm_domain *genpd, struct device *dev, struct device *base_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058ff10)
Location: drivers/base/power/domain.c:1498
Inline: False
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffe00058ff10-ffffffe000590196: genpd_add_device (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816dd9d3)
Location: drivers/base/power/domain.c:1498
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b8043)
Location: drivers/base/power/domain.c:1498
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8170b363)
Location: drivers/base/power/domain.c:1498
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817254f3)
Location: drivers/base/power/domain.c:1498
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_device
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
