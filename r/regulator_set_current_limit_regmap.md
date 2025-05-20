# Function: <code>regulator_set_current_limit_regmap</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff8165dd40)
Location: drivers/regulator/helpers.c:789
Inline: False
```
**Symbols:**

```
ffffffff8165dd40-ffffffff8165ddf3: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff816804b0)
Location: drivers/regulator/helpers.c:791
Inline: False
```
**Symbols:**

```
ffffffff816804b0-ffffffff81680563: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff817313b0)
Location: drivers/regulator/helpers.c:775
Inline: False
```
**Symbols:**

```
ffffffff817313b0-ffffffff81731465: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff8174d490)
Location: drivers/regulator/helpers.c:777
Inline: False
```
**Symbols:**

```
ffffffff8174d490-ffffffff8174d545: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff81730f10)
Location: drivers/regulator/helpers.c:797
Inline: False
```
**Symbols:**

```
ffffffff81730f10-ffffffff81730fc3: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/helpers.c (0)
Location: drivers/regulator/helpers.c:797
Inline: False
```
**Symbols:**

```
ffffffff81cf82b9-ffffffff81cf82e4: regulator_set_current_limit_regmap.cold (STB_LOCAL)
ffffffff817b0dc0-ffffffff817b0e94: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/helpers.c (0)
Location: drivers/regulator/helpers.c:797
Inline: False
```
**Symbols:**

```
ffffffff81ec03b0-ffffffff81ec03db: regulator_set_current_limit_regmap.cold (STB_LOCAL)
ffffffff818ec350-ffffffff818ec457: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/helpers.c (0)
Location: drivers/regulator/helpers.c:797
Inline: False
```
**Symbols:**

```
ffffffff82094bc8-ffffffff82094bf3: regulator_set_current_limit_regmap.cold (STB_LOCAL)
ffffffff81a436b0-ffffffff81a437b7: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/helpers.c (0)
Location: drivers/regulator/helpers.c:797
Inline: False
```
**Symbols:**

```
ffffffff821159ec-ffffffff82115a17: regulator_set_current_limit_regmap.cold (STB_LOCAL)
ffffffff81a8d890-ffffffff81a8d997: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/helpers.c (0)
Location: drivers/regulator/helpers.c:800
Inline: False
```
**Symbols:**

```
ffffffff821f36a3-ffffffff821f36ce: regulator_set_current_limit_regmap.cold (STB_LOCAL)
ffffffff81ae00c0-ffffffff81ae01c7: regulator_set_current_limit_regmap (STB_GLOBAL)
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
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffff800010849f28)
Location: drivers/regulator/helpers.c:791
Inline: False
```
**Symbols:**

```
ffff800010849f28-ffff80001084a024: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (c0953600)
Location: drivers/regulator/helpers.c:791
Inline: False
```
**Symbols:**

```
c0953600-c09536ec: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (c0000000008e7500)
Location: drivers/regulator/helpers.c:791
Inline: False
```
**Symbols:**

```
c0000000008e7500-c0000000008e7648: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffe000529fd8)
Location: drivers/regulator/helpers.c:791
Inline: False
```
**Symbols:**

```
ffffffe000529fd8-ffffffe00052a0e0: regulator_set_current_limit_regmap (STB_GLOBAL)
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
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff81645f30)
Location: drivers/regulator/helpers.c:791
Inline: False
```
**Symbols:**

```
ffffffff81645f30-ffffffff81645fe3: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff81626390)
Location: drivers/regulator/helpers.c:791
Inline: False
```
**Symbols:**

```
ffffffff81626390-ffffffff81626443: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff816742f0)
Location: drivers/regulator/helpers.c:791
Inline: False
```
**Symbols:**

```
ffffffff816742f0-ffffffff816743a3: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regulator_set_current_limit_regmap(struct regulator_dev *rdev, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff8168e950)
Location: drivers/regulator/helpers.c:791
Inline: False
```
**Symbols:**

```
ffffffff8168e950-ffffffff8168ea03: regulator_set_current_limit_regmap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
