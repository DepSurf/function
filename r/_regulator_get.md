# Function: <code>_regulator_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, bool exclusive, bool allow_dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dc650)
Location: drivers/regulator/core.c:1530
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/core.c:regulator_get_optional
```
**Symbols:**

```
ffffffff814dc650-ffffffff814dc8dc: _regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, bool exclusive, bool allow_dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152e220)
Location: drivers/regulator/core.c:1582
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/core.c:regulator_get
```
**Symbols:**

```
ffffffff8152e220-ffffffff8152e499: _regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, bool exclusive, bool allow_dummy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81559f30)
Location: drivers/regulator/core.c:1583
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
```
**Symbols:**

```
ffffffff81559f30-ffffffff8155a1a9: _regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156fe30)
Location: drivers/regulator/core.c:1589
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff8156fe30-ffffffff815700af: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d40c0)
Location: drivers/regulator/core.c:1589
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff815d40c0-ffffffff815d433f: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1640
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff8160d2b3-ffffffff8160d2cb: _regulator_get.cold.68 (STB_LOCAL)
ffffffff8160c000-ffffffff8160c256: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1853
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff81629958-ffffffff81629970: _regulator_get.cold.75 (STB_LOCAL)
ffffffff81628680-ffffffff81628900: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1835
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff8165d03d-ffffffff8165d0ea: _regulator_get.cold (STB_LOCAL)
ffffffff8165aa40-ffffffff8165ac4d: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1843
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff8167fa1f-ffffffff8167facc: _regulator_get.cold (STB_LOCAL)
ffffffff8167ef10-ffffffff8167f11d: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1862
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff81730882-ffffffff81730926: _regulator_get.cold (STB_LOCAL)
ffffffff8172ea20-ffffffff8172ec34: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1919
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff81c06de5-ffffffff81c06e89: _regulator_get.cold (STB_LOCAL)
ffffffff8174b6c0-ffffffff8174b8d4: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1930
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff81bf8a80-ffffffff81bf8b24: _regulator_get.cold (STB_LOCAL)
ffffffff8172edd0-ffffffff8172efe4: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2030
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff81cf7c9a-ffffffff81cf7d52: _regulator_get.cold (STB_LOCAL)
ffffffff817aea80-ffffffff817aeca3: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2074
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff81ec0127-ffffffff81ec01c9: _regulator_get.cold (STB_LOCAL)
ffffffff818ea420-ffffffff818ea655: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a42b28)
Location: drivers/regulator/core.c:2101
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/core.c:regulator_get
Direct callers:
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/core.c:regulator_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff81a40330-ffffffff81a405b3: _regulator_get.part.0 (STB_LOCAL)
ffffffff82094b68-ffffffff82094b7d: _regulator_get.part.0.cold (STB_LOCAL)
ffffffff81a405d0-ffffffff81a4062c: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a8cc31)
Location: drivers/regulator/core.c:2165
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/core.c:regulator_get
Direct callers:
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/core.c:regulator_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff81a8a2e0-ffffffff81a8a652: _regulator_get.part.0 (STB_LOCAL)
ffffffff8211598c-ffffffff821159a1: _regulator_get.part.0.cold (STB_LOCAL)
ffffffff81a8a670-ffffffff81a8a6cc: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adf431)
Location: drivers/regulator/core.c:2167
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/core.c:regulator_get
Direct callers:
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/core.c:regulator_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff81adca30-ffffffff81adcda2: _regulator_get.part.0 (STB_LOCAL)
ffffffff821f3643-ffffffff821f3658: _regulator_get.part.0.cold (STB_LOCAL)
ffffffff81adcdc0-ffffffff81adce1c: _regulator_get (STB_GLOBAL)
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
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010848e00)
Location: drivers/regulator/core.c:1843
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffff800010848e00-ffff8000108490c0: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c095261c)
Location: drivers/regulator/core.c:1843
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
c095261c-c09528a4: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e5e40)
Location: drivers/regulator/core.c:1843
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
c0000000008e5e40-c0000000008e622c: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000528f2c)
Location: drivers/regulator/core.c:1843
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffe000528f2c-ffffffe000529154: _regulator_get (STB_GLOBAL)
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
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1843
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff8164549f-ffffffff8164554c: _regulator_get.cold (STB_LOCAL)
ffffffff81644970-ffffffff81644b7d: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1843
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff816258ff-ffffffff816259ac: _regulator_get.cold (STB_LOCAL)
ffffffff81624df0-ffffffff81624ffd: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1843
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff8167385f-ffffffff8167390c: _regulator_get.cold (STB_LOCAL)
ffffffff81672d50-ffffffff81672f5d: _regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct regulator *_regulator_get(struct device *dev, const char *id, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1843
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:regulator_get_optional
  - drivers/regulator/core.c:regulator_get_exclusive
  - drivers/regulator/devres.c:_devm_regulator_get
```
**Symbols:**

```
ffffffff8168debf-ffffffff8168df6c: _regulator_get.cold (STB_LOCAL)
ffffffff8168d3b0-ffffffff8168d5bd: _regulator_get (STB_GLOBAL)
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
<b>Param added. </b>
<code>enum regulator_get_type get_type</code>
</li>
<li>
<b>Param removed. </b>
<code>bool exclusive</code>
</li>
<li>
<b>Param removed. </b>
<code>bool allow_dummy</code>
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
