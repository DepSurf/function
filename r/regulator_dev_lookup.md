# Function: <code>regulator_dev_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply, int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d8490)
Location: drivers/regulator/core.c:1409
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
ffffffff814d8490-ffffffff814d86b0: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply, int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81529250)
Location: drivers/regulator/core.c:1460
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81529250-ffffffff81529460: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply, int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81555760)
Location: drivers/regulator/core.c:1461
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81555760-ffffffff81555970: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81569d80)
Location: drivers/regulator/core.c:1462
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81569d80-ffffffff81569f93: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815cdf60)
Location: drivers/regulator/core.c:1462
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff815cdf60-ffffffff815ce16f: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816063e0)
Location: drivers/regulator/core.c:1513
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff816063e0-ffffffff816065e7: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81621600)
Location: drivers/regulator/core.c:1722
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81621600-ffffffff81621807: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81654890)
Location: drivers/regulator/core.c:1704
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81654890-ffffffff81654a96: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81676d80)
Location: drivers/regulator/core.c:1712
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81676d80-ffffffff81676f86: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81727890)
Location: drivers/regulator/core.c:1731
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81727890-ffffffff81727a4e: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81744310)
Location: drivers/regulator/core.c:1757
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81744310-ffffffff817444ce: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81727c30)
Location: drivers/regulator/core.c:1768
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81727c30-ffffffff81727e68: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817a6d80)
Location: drivers/regulator/core.c:1868
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff817a6d80-ffffffff817a6fb8: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e1300)
Location: drivers/regulator/core.c:1912
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff818e1300-ffffffff818e1567: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a36490)
Location: drivers/regulator/core.c:1938
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81a36490-ffffffff81a366f7: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a7ff40)
Location: drivers/regulator/core.c:2001
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81a7ff40-ffffffff81a801c6: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad24b0)
Location: drivers/regulator/core.c:2003
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81ad24b0-ffffffff81ad2736: regulator_dev_lookup (STB_LOCAL)
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
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff80001083fc50)
Location: drivers/regulator/core.c:1712
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffff80001083fc50-ffff80001083fe8c: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0949498)
Location: drivers/regulator/core.c:1712
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
c0949498-c0949714: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008d9310)
Location: drivers/regulator/core.c:1712
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
c0000000008d9310-c0000000008d9960: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000521c28)
Location: drivers/regulator/core.c:1712
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffe000521c28-ffffffe000521e36: regulator_dev_lookup (STB_LOCAL)
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
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163ca70)
Location: drivers/regulator/core.c:1712
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8163ca70-ffffffff8163cc76: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8161cc60)
Location: drivers/regulator/core.c:1712
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8161cc60-ffffffff8161ce66: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166abc0)
Location: drivers/regulator/core.c:1712
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8166abc0-ffffffff8166adc6: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct regulator_dev *regulator_dev_lookup(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81685180)
Location: drivers/regulator/core.c:1712
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81685180-ffffffff81685386: regulator_dev_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *ret</code>
</li>
</ul>
</details>
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
