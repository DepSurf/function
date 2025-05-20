# Function: <code>regulator_resolve_supply</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dc400)
Location: drivers/regulator/core.c:1466
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
ffffffff814dc400-ffffffff814dc64b: regulator_resolve_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152df60)
Location: drivers/regulator/core.c:1517
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8152df60-ffffffff8152e1a5: regulator_resolve_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81559c70)
Location: drivers/regulator/core.c:1518
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81559c70-ffffffff81559eb5: regulator_resolve_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156e210)
Location: drivers/regulator/core.c:1517
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8156e210-ffffffff8156e445: regulator_resolve_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d24a0)
Location: drivers/regulator/core.c:1517
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff815d24a0-ffffffff815d26d5: regulator_resolve_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1568
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8160a8d0-ffffffff8160a9c4: regulator_resolve_supply (STB_LOCAL)
ffffffff8160cc90-ffffffff8160cdb6: regulator_resolve_supply.cold.65 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1777
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81627260-ffffffff81627354: regulator_resolve_supply (STB_LOCAL)
ffffffff81629266-ffffffff81629370: regulator_resolve_supply.cold.69 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1759
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8165a910-ffffffff8165aa3f: regulator_resolve_supply (STB_LOCAL)
ffffffff8165cf5a-ffffffff8165d03d: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1767
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8167d510-ffffffff8167d63f: regulator_resolve_supply (STB_LOCAL)
ffffffff8167f74a-ffffffff8167f82d: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1786
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8172e930-ffffffff8172ea1e: regulator_resolve_supply (STB_LOCAL)
ffffffff81730799-ffffffff81730882: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1812
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8174b500-ffffffff8174b6b6: regulator_resolve_supply (STB_LOCAL)
ffffffff81c06c9e-ffffffff81c06de5: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1823
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8172ec10-ffffffff8172edc6: regulator_resolve_supply (STB_LOCAL)
ffffffff81bf8939-ffffffff81bf8a80: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1923
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff817ae850-ffffffff817aea79: regulator_resolve_supply (STB_LOCAL)
ffffffff81cf7b43-ffffffff81cf7c9a: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1967
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff818e9fe0-ffffffff818ea41f: regulator_resolve_supply (STB_LOCAL)
ffffffff81ec00a8-ffffffff81ec0127: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1994
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81a3fec0-ffffffff81a40315: regulator_resolve_supply (STB_LOCAL)
ffffffff82094b3e-ffffffff82094b68: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2057
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81a89a90-ffffffff81a8a2c4: regulator_resolve_supply (STB_LOCAL)
ffffffff82115962-ffffffff8211598c: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2059
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81adc1e0-ffffffff81adca14: regulator_resolve_supply (STB_LOCAL)
ffffffff821f3619-ffffffff821f3643: regulator_resolve_supply.cold (STB_LOCAL)
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
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010847150)
Location: drivers/regulator/core.c:1767
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffff800010847150-ffff80001084734c: regulator_resolve_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0950900)
Location: drivers/regulator/core.c:1767
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
c0950900-c0950b08: regulator_resolve_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e33e0)
Location: drivers/regulator/core.c:1767
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
c0000000008e33e0-c0000000008e3668: regulator_resolve_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000527526)
Location: drivers/regulator/core.c:1767
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffe000527526-ffffffe0005276d0: regulator_resolve_supply (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1767
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81642df0-ffffffff81642f1f: regulator_resolve_supply (STB_LOCAL)
ffffffff81645163-ffffffff81645246: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1767
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff816233f0-ffffffff8162351f: regulator_resolve_supply (STB_LOCAL)
ffffffff8162562a-ffffffff8162570d: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1767
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff81671350-ffffffff8167147f: regulator_resolve_supply (STB_LOCAL)
ffffffff8167358a-ffffffff8167366d: regulator_resolve_supply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_resolve_supply(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1767
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff8168b9b0-ffffffff8168badf: regulator_resolve_supply (STB_LOCAL)
ffffffff8168dbea-ffffffff8168dccd: regulator_resolve_supply.cold (STB_LOCAL)
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
