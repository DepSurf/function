# Function: <code>genpd_alloc_dev_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815b0a5a)
Location: drivers/base/power/domain.c:996
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815dfee6)
Location: drivers/base/power/domain.c:1106
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
In drivers/base/power/domain.c (ffffffff815f4d9a)
Location: drivers/base/power/domain.c:1189
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
In drivers/base/power/domain.c (ffffffff8165cc9a)
Location: drivers/base/power/domain.c:1312
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
In drivers/base/power/domain.c (ffffffff816989d9)
Location: drivers/base/power/domain.c:1318
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
In drivers/base/power/domain.c (ffffffff816b9229)
Location: drivers/base/power/domain.c:1397
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
In drivers/base/power/domain.c (ffffffff816f3274)
Location: drivers/base/power/domain.c:1400
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
In drivers/base/power/domain.c (ffffffff817176d4)
Location: drivers/base/power/domain.c:1395
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
struct generic_pm_domain_data *genpd_alloc_dev_data(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d2810)
Location: drivers/base/power/domain.c:1384
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
ffffffff817d2810-ffffffff817d28f4: genpd_alloc_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct generic_pm_domain_data *genpd_alloc_dev_data(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e6f50)
Location: drivers/base/power/domain.c:1449
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
ffffffff817e6f50-ffffffff817e7034: genpd_alloc_dev_data (STB_LOCAL)
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
In drivers/base/power/domain.c (ffffffff817cc14c)
Location: drivers/base/power/domain.c:1444
Inline: True
Inline callers:
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
In drivers/base/power/domain.c (ffffffff8185681c)
Location: drivers/base/power/domain.c:1484
Inline: True
Inline callers:
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
In drivers/base/power/domain.c (ffffffff8199b4cb)
Location: drivers/base/power/domain.c:1502
Inline: True
Inline callers:
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
In drivers/base/power/domain.c (ffffffff81b0c68c)
Location: drivers/base/power/domain.c:1481
Inline: True
Inline callers:
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
In drivers/base/power/domain.c (ffffffff81b5a6a0)
Location: drivers/base/power/domain.c:1507
Inline: True
Inline callers:
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
In drivers/pmdomain/core.c (ffffffff81aa2100)
Location: drivers/pmdomain/core.c:1514
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_add_device
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010909fb8)
Location: drivers/base/power/domain.c:1395
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f14c0)
Location: drivers/base/power/domain.c:1395
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009aa214)
Location: drivers/base/power/domain.c:1395
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058ff58)
Location: drivers/base/power/domain.c:1395
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_device
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
In drivers/base/power/domain.c (ffffffff816dda04)
Location: drivers/base/power/domain.c:1395
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
In drivers/base/power/domain.c (ffffffff816b8074)
Location: drivers/base/power/domain.c:1395
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
In drivers/base/power/domain.c (ffffffff8170b394)
Location: drivers/base/power/domain.c:1395
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
In drivers/base/power/domain.c (ffffffff81725524)
Location: drivers/base/power/domain.c:1395
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
</ul>
