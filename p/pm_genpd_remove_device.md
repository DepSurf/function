# Function: <code>pm_genpd_remove_device</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pm_genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815b0ce0)
Location: drivers/base/power/domain.c:1113
Inline: True
```
**Symbols:**

```
ffffffff815b0ce0-ffffffff815b0df3: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815dfcd0)
Location: drivers/base/power/domain.c:1276
Inline: False
```
**Symbols:**

```
ffffffff815dfcd0-ffffffff815dfe82: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f4b70)
Location: drivers/base/power/domain.c:1359
Inline: False
```
**Symbols:**

```
ffffffff815f4b70-ffffffff815f4d33: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct generic_pm_domain *genpd, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165ca60)
Location: drivers/base/power/domain.c:1482
Inline: False
```
**Symbols:**

```
ffffffff8165ca60-ffffffff8165cc38: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816987b0)
Location: drivers/base/power/domain.c:1479
Inline: False
```
**Symbols:**

```
ffffffff816987b0-ffffffff81698976: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b9000)
Location: drivers/base/power/domain.c:1558
Inline: False
```
**Symbols:**

```
ffffffff816b9000-ffffffff816b91c6: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816f3020)
Location: drivers/base/power/domain.c:1611
Inline: False
```
**Symbols:**

```
ffffffff816f3020-ffffffff816f321a: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817174f0)
Location: drivers/base/power/domain.c:1606
Inline: False
```
**Symbols:**

```
ffffffff817174f0-ffffffff8171767d: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d27b0)
Location: drivers/base/power/domain.c:1595
Inline: False
```
**Symbols:**

```
ffffffff817d27b0-ffffffff817d2802: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e6ef0)
Location: drivers/base/power/domain.c:1660
Inline: False
```
**Symbols:**

```
ffffffff817e6ef0-ffffffff817e6f42: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817cb700)
Location: drivers/base/power/domain.c:1656
Inline: False
```
**Symbols:**

```
ffffffff817cb700-ffffffff817cb752: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81855720)
Location: drivers/base/power/domain.c:1696
Inline: False
```
**Symbols:**

```
ffffffff81855720-ffffffff81855772: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199be60)
Location: drivers/base/power/domain.c:1732
Inline: False
```
**Symbols:**

```
ffffffff8199be60-ffffffff8199bed9: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0d120)
Location: drivers/base/power/domain.c:1711
Inline: False
```
**Symbols:**

```
ffffffff81b0d120-ffffffff81b0d199: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5b090)
Location: drivers/base/power/domain.c:1737
Inline: False
```
**Symbols:**

```
ffffffff81b5b090-ffffffff81b5b109: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa2b60)
Location: drivers/pmdomain/core.c:1744
Inline: False
```
**Symbols:**

```
ffffffff81aa2b60-ffffffff81aa2bd9: pm_genpd_remove_device (STB_GLOBAL)
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
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010909bd0)
Location: drivers/base/power/domain.c:1606
Inline: False
```
**Symbols:**

```
ffff800010909bd0-ffff800010909c44: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f18e8)
Location: drivers/base/power/domain.c:1606
Inline: False
```
**Symbols:**

```
c09f18e8-c09f194c: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a91f0)
Location: drivers/base/power/domain.c:1606
Inline: False
```
**Symbols:**

```
c0000000009a91f0-c0000000009a925c: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058fbac)
Location: drivers/base/power/domain.c:1606
Inline: False
```
**Symbols:**

```
ffffffe00058fbac-ffffffe00058fc08: pm_genpd_remove_device (STB_GLOBAL)
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
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816dd820)
Location: drivers/base/power/domain.c:1606
Inline: False
```
**Symbols:**

```
ffffffff816dd820-ffffffff816dd9ad: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b7e90)
Location: drivers/base/power/domain.c:1606
Inline: False
```
**Symbols:**

```
ffffffff816b7e90-ffffffff816b801d: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8170b1b0)
Location: drivers/base/power/domain.c:1606
Inline: False
```
**Symbols:**

```
ffffffff8170b1b0-ffffffff8170b33d: pm_genpd_remove_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pm_genpd_remove_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81724c60)
Location: drivers/base/power/domain.c:1606
Inline: False
```
**Symbols:**

```
ffffffff81724c60-ffffffff81724ded: pm_genpd_remove_device (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct generic_pm_domain *genpd</code>
</li>
<li>
<b>Param reordered. </b>
<code>genpd, dev</code> ➡️ <code>dev</code>
</li>
</ul>
</details>
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
