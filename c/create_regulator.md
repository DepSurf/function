# Function: <code>create_regulator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dc110)
Location: drivers/regulator/core.c:1260
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
ffffffff814dc110-ffffffff814dc3fb: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152dc50)
Location: drivers/regulator/core.c:1308
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8152dc50-ffffffff8152df58: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81559960)
Location: drivers/regulator/core.c:1309
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81559960-ffffffff81559c68: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156df10)
Location: drivers/regulator/core.c:1309
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8156df10-ffffffff8156e204: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d21a0)
Location: drivers/regulator/core.c:1309
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff815d21a0-ffffffff815d2494: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1374
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8160a590-ffffffff8160a8c5: create_regulator (STB_LOCAL)
ffffffff8160cc7b-ffffffff8160cc90: create_regulator.cold.64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1583
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81625970-ffffffff81625d00: create_regulator (STB_LOCAL)
ffffffff816290da-ffffffff816290ef: create_regulator.cold.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81657fa0)
Location: drivers/regulator/core.c:1565
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81657fa0-ffffffff8165832e: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167bec0)
Location: drivers/regulator/core.c:1573
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8167bec0-ffffffff8167c24e: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1589
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8172ce40-ffffffff8172d1af: create_regulator (STB_LOCAL)
ffffffff81730610-ffffffff8173062c: create_regulator.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1615
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81749f10-ffffffff8174a29b: create_regulator (STB_LOCAL)
ffffffff81c06b42-ffffffff81c06b5e: create_regulator.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1626
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8172d780-ffffffff8172db0b: create_regulator (STB_LOCAL)
ffffffff81bf87dd-ffffffff81bf87f9: create_regulator.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1726
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff817ad2f0-ffffffff817ad6d9: create_regulator (STB_LOCAL)
ffffffff81cf7900-ffffffff81cf791c: create_regulator.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1770
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff818e7f70-ffffffff818e8354: create_regulator (STB_LOCAL)
ffffffff81ebfacf-ffffffff81ebfaeb: create_regulator.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3baf0)
Location: drivers/regulator/core.c:1796
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81a3baf0-ffffffff81a3bf04: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a85370)
Location: drivers/regulator/core.c:1861
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81a85370-ffffffff81a856e1: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad7b50)
Location: drivers/regulator/core.c:1863
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81ad7b50-ffffffff81ad7ea4: create_regulator (STB_LOCAL)
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
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010845a20)
Location: drivers/regulator/core.c:1573
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffff800010845a20-ffff800010845d5c: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094f130)
Location: drivers/regulator/core.c:1573
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
c094f130-c094f4b0: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e1350)
Location: drivers/regulator/core.c:1573
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
c0000000008e1350-c0000000008e17c4: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005261c4)
Location: drivers/regulator/core.c:1573
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffe0005261c4-ffffffe0005264bc: create_regulator (STB_LOCAL)
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
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816417a0)
Location: drivers/regulator/core.c:1573
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff816417a0-ffffffff81641b2e: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81621da0)
Location: drivers/regulator/core.c:1573
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81621da0-ffffffff8162212e: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166fd00)
Location: drivers/regulator/core.c:1573
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8166fd00-ffffffff8167008e: create_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct regulator *create_regulator(struct regulator_dev *rdev, struct device *dev, const char *supply_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168a360)
Location: drivers/regulator/core.c:1573
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8168a360-ffffffff8168a6ee: create_regulator (STB_LOCAL)
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
