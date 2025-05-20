# Function: <code>dev_pm_genpd_remove_notifier</code>

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
int dev_pm_genpd_remove_notifier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1732
Inline: False
```
**Symbols:**

```
ffffffff81c0f038-ffffffff81c0f053: dev_pm_genpd_remove_notifier.cold (STB_LOCAL)
ffffffff817e7520-ffffffff817e7669: dev_pm_genpd_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_pm_genpd_remove_notifier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1728
Inline: False
```
**Symbols:**

```
ffffffff81c011a2-ffffffff81c011bd: dev_pm_genpd_remove_notifier.cold (STB_LOCAL)
ffffffff817cb430-ffffffff817cb579: dev_pm_genpd_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_pm_genpd_remove_notifier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1768
Inline: False
```
**Symbols:**

```
ffffffff81d03fe3-ffffffff81d03ffe: dev_pm_genpd_remove_notifier.cold (STB_LOCAL)
ffffffff81855450-ffffffff81855599: dev_pm_genpd_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_pm_genpd_remove_notifier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1804
Inline: False
```
**Symbols:**

```
ffffffff81ecc8d9-ffffffff81ecc8f5: dev_pm_genpd_remove_notifier.cold (STB_LOCAL)
ffffffff8199c1c0-ffffffff8199c2e7: dev_pm_genpd_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_pm_genpd_remove_notifier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0d380)
Location: drivers/base/power/domain.c:1783
Inline: False
```
**Symbols:**

```
ffffffff81b0d380-ffffffff81b0d4bf: dev_pm_genpd_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_pm_genpd_remove_notifier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5b430)
Location: drivers/base/power/domain.c:1809
Inline: False
```
**Symbols:**

```
ffffffff81b5b430-ffffffff81b5b56f: dev_pm_genpd_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_pm_genpd_remove_notifier(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa2f30)
Location: drivers/pmdomain/core.c:1816
Inline: False
```
**Symbols:**

```
ffffffff81aa2f30-ffffffff81aa306f: dev_pm_genpd_remove_notifier (STB_GLOBAL)
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
