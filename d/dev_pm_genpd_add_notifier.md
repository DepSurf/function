# Function: <code>dev_pm_genpd_add_notifier</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_pm_genpd_add_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1686
Inline: False
```
**Symbols:**

```
ffffffff81c0f01d-ffffffff81c0f038: dev_pm_genpd_add_notifier.cold (STB_LOCAL)
ffffffff817e73d0-ffffffff817e7515: dev_pm_genpd_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_pm_genpd_add_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1682
Inline: False
```
**Symbols:**

```
ffffffff81c01187-ffffffff81c011a2: dev_pm_genpd_add_notifier.cold (STB_LOCAL)
ffffffff817cb2e0-ffffffff817cb422: dev_pm_genpd_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_pm_genpd_add_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1722
Inline: False
```
**Symbols:**

```
ffffffff81d03fc8-ffffffff81d03fe3: dev_pm_genpd_add_notifier.cold (STB_LOCAL)
ffffffff81855300-ffffffff81855442: dev_pm_genpd_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_pm_genpd_add_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1758
Inline: False
```
**Symbols:**

```
ffffffff81ecc8bd-ffffffff81ecc8d9: dev_pm_genpd_add_notifier.cold (STB_LOCAL)
ffffffff8199c0a0-ffffffff8199c1b7: dev_pm_genpd_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_pm_genpd_add_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0d230)
Location: drivers/base/power/domain.c:1737
Inline: False
```
**Symbols:**

```
ffffffff81b0d230-ffffffff81b0d363: dev_pm_genpd_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_pm_genpd_add_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5b2e0)
Location: drivers/base/power/domain.c:1763
Inline: False
```
**Symbols:**

```
ffffffff81b5b2e0-ffffffff81b5b413: dev_pm_genpd_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_pm_genpd_add_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa2de0)
Location: drivers/pmdomain/core.c:1770
Inline: False
```
**Symbols:**

```
ffffffff81aa2de0-ffffffff81aa2f13: dev_pm_genpd_add_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
