# Function: <code>genpd_dev_pm_attach_by_id</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:287
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:320
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:343
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:343
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:351
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:375
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:387
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:389
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:393
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:400
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:405
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:398
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct device *genpd_dev_pm_attach_by_id(struct device *dev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff80001090a628)
Location: drivers/base/power/domain.c:2499
Inline: True
Direct callers:
  - drivers/base/power/common.c:dev_pm_domain_attach_by_id
  - drivers/base/power/domain.c:genpd_dev_pm_attach_by_name
```
**Symbols:**

```
ffff80001090a628-ffff80001090a7a0: genpd_dev_pm_attach_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device *genpd_dev_pm_attach_by_id(struct device *dev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f37bc)
Location: drivers/base/power/domain.c:2499
Inline: True
Direct callers:
  - drivers/base/power/common.c:dev_pm_domain_attach_by_id
  - drivers/base/power/domain.c:genpd_dev_pm_attach_by_name
```
**Symbols:**

```
c09f37bc-c09f3910: genpd_dev_pm_attach_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device *genpd_dev_pm_attach_by_id(struct device *dev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009aaac0)
Location: drivers/base/power/domain.c:2499
Inline: True
Direct callers:
  - drivers/base/power/common.c:dev_pm_domain_attach_by_id
  - drivers/base/power/domain.c:genpd_dev_pm_attach_by_name
```
**Symbols:**

```
c0000000009aaac0-c0000000009aacf8: genpd_dev_pm_attach_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device *genpd_dev_pm_attach_by_id(struct device *dev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe000590486)
Location: drivers/base/power/domain.c:2499
Inline: True
Direct callers:
  - drivers/base/power/common.c:dev_pm_domain_attach_by_id
  - drivers/base/power/domain.c:genpd_dev_pm_attach_by_name
```
**Symbols:**

```
ffffffe000590486-ffffffe0005905b8: genpd_dev_pm_attach_by_id (STB_GLOBAL)
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:343
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:343
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:343
Inline: True
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
In drivers/base/power/common.c (0)
Location: include/linux/pm_domain.h:343
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
