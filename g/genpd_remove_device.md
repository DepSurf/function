# Function: <code>genpd_remove_device</code>

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
In drivers/base/power/domain.c (ffffffff815dfd84)
Location: drivers/base/power/domain.c:1230
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
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
In drivers/base/power/domain.c (ffffffff815f4c24)
Location: drivers/base/power/domain.c:1311
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
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
In drivers/base/power/domain.c (ffffffff8165cb14)
Location: drivers/base/power/domain.c:1434
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
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
In drivers/base/power/domain.c (ffffffff81698860)
Location: drivers/base/power/domain.c:1432
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
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
In drivers/base/power/domain.c (ffffffff816b90b0)
Location: drivers/base/power/domain.c:1511
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
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
In drivers/base/power/domain.c (ffffffff816f30d2)
Location: drivers/base/power/domain.c:1562
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
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
In drivers/base/power/domain.c (ffffffff81717555)
Location: drivers/base/power/domain.c:1557
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d2630)
Location: drivers/base/power/domain.c:1546
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff817d2630-ffffffff817d27ac: genpd_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e6d70)
Location: drivers/base/power/domain.c:1611
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff817e6d70-ffffffff817e6eec: genpd_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817cb580)
Location: drivers/base/power/domain.c:1607
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff817cb580-ffffffff817cb6fc: genpd_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff818555a0)
Location: drivers/base/power/domain.c:1647
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff818555a0-ffffffff8185571c: genpd_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199b810)
Location: drivers/base/power/domain.c:1682
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff8199b810-ffffffff8199b99a: genpd_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0c9f0)
Location: drivers/base/power/domain.c:1661
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff81b0c9f0-ffffffff81b0cb7a: genpd_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5a9f0)
Location: drivers/base/power/domain.c:1687
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff81b5a9f0-ffffffff81b5ab7a: genpd_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa24b0)
Location: drivers/pmdomain/core.c:1694
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff81aa24b0-ffffffff81aa263a: genpd_remove_device (STB_LOCAL)
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
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010909a88)
Location: drivers/base/power/domain.c:1557
Inline: False
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffff800010909a88-ffff800010909bcc: genpd_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f17a8)
Location: drivers/base/power/domain.c:1557
Inline: False
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
c09f17a8-c09f18e8: genpd_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a9030)
Location: drivers/base/power/domain.c:1557
Inline: False
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
c0000000009a9030-c0000000009a91e4: genpd_remove_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058fa92)
Location: drivers/base/power/domain.c:1557
Inline: False
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffe00058fa92-ffffffe00058fbac: genpd_remove_device (STB_LOCAL)
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
In drivers/base/power/domain.c (ffffffff816dd885)
Location: drivers/base/power/domain.c:1557
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
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
In drivers/base/power/domain.c (ffffffff816b7ef5)
Location: drivers/base/power/domain.c:1557
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
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
In drivers/base/power/domain.c (ffffffff8170b215)
Location: drivers/base/power/domain.c:1557
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
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
In drivers/base/power/domain.c (ffffffff81724cc5)
Location: drivers/base/power/domain.c:1557
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
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
