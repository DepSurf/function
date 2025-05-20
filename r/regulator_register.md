# Function: <code>regulator_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dd2a0)
Location: drivers/regulator/core.c:3839
Inline: True
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff814dd2a0-ffffffff814ddb40: regulator_register.part.29 (STB_LOCAL)
ffffffff814ddb40-ffffffff814ddb62: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152e5e0)
Location: drivers/regulator/core.c:3883
Inline: True
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff8152e5e0-ffffffff8152ef07: regulator_register.part.31 (STB_LOCAL)
ffffffff8152ef10-ffffffff8152ef32: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8155ac40)
Location: drivers/regulator/core.c:3947
Inline: True
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff8155ac40-ffffffff8155b584: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156ef40)
Location: drivers/regulator/core.c:3966
Inline: True
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff8156ef40-ffffffff8156f86c: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d31f0)
Location: drivers/regulator/core.c:3974
Inline: True
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff815d31f0-ffffffff815d3b0e: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8160ba30)
Location: drivers/regulator/core.c:4232
Inline: True
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff8160b100-ffffffff8160ba27: regulator_register.part.32 (STB_LOCAL)
ffffffff8160d277-ffffffff8160d2b3: regulator_register.part.32.cold.67 (STB_LOCAL)
ffffffff8160ba30-ffffffff8160ba52: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4868
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff81629880-ffffffff816298c0: regulator_register.cold.72 (STB_LOCAL)
ffffffff816279c0-ffffffff81628415: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4977
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff8165d368-ffffffff8165d3ca: regulator_register.cold (STB_LOCAL)
ffffffff8165bd90-ffffffff8165c6c0: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4987
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff8167f92b-ffffffff8167f947: regulator_register.cold (STB_LOCAL)
ffffffff8167dbd0-ffffffff8167e59e: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:5041
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff81730b36-ffffffff81730b8b: regulator_register.cold (STB_LOCAL)
ffffffff8172f300-ffffffff8172f927: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:5176
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff81c070e3-ffffffff81c07130: regulator_register.cold (STB_LOCAL)
ffffffff8174bf30-ffffffff8174c5fb: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:5178
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff81bf8d7e-ffffffff81bf8ddf: regulator_register.cold (STB_LOCAL)
ffffffff8172f6c0-ffffffff8172fe9b: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:5315
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff81cf8100-ffffffff81cf8161: regulator_register.cold (STB_LOCAL)
ffffffff817af4b0-ffffffff817afc97: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:5380
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff81ec01e3-ffffffff81ec0244: regulator_register.cold (STB_LOCAL)
ffffffff818ea880-ffffffff818eb092: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct regulator_dev *regulator_register(struct device *dev, const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a413a0)
Location: drivers/regulator/core.c:5422
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff81a413a0-ffffffff81a41d5f: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct regulator_dev *regulator_register(struct device *dev, const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a8b470)
Location: drivers/regulator/core.c:5486
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff81a8b470-ffffffff81a8be52: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct regulator_dev *regulator_register(struct device *dev, const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81addbc0)
Location: drivers/regulator/core.c:5545
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff81addbc0-ffffffff81ade653: regulator_register (STB_GLOBAL)
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
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010847940)
Location: drivers/regulator/core.c:4987
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffff800010847940-ffff800010848344: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c095118c)
Location: drivers/regulator/core.c:4987
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
c095118c-c0951b60: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e3e80)
Location: drivers/regulator/core.c:4987
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
c0000000008e3e80-c0000000008e4f54: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000527d16)
Location: drivers/regulator/core.c:4987
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffe000527d16-ffffffe000528682: regulator_register (STB_GLOBAL)
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
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4987
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff816453ab-ffffffff816453c7: regulator_register.cold (STB_LOCAL)
ffffffff81643630-ffffffff81643ffe: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4987
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff8162580b-ffffffff81625827: regulator_register.cold (STB_LOCAL)
ffffffff81623ab0-ffffffff8162447e: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4987
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff8167376b-ffffffff81673787: regulator_register.cold (STB_LOCAL)
ffffffff81671a10-ffffffff816723de: regulator_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct regulator_dev *regulator_register(const struct regulator_desc *regulator_desc, const struct regulator_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4987
Inline: False
Direct callers:
  - drivers/regulator/dummy.c:dummy_regulator_probe
  - drivers/regulator/devres.c:devm_regulator_register
```
**Symbols:**

```
ffffffff8168ddcb-ffffffff8168dde7: regulator_register.cold (STB_LOCAL)
ffffffff8168c070-ffffffff8168ca3e: regulator_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>regulator_desc, cfg</code> ➡️ <code>dev, regulator_desc, cfg</code>
</li>
</ul>
</details>
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
