# Function: <code>devm_regulator_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff814de9b0)
Location: drivers/regulator/devres.c:131
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff814de9b0-ffffffff814de9e9: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8152fdb0)
Location: drivers/regulator/devres.c:131
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff8152fdb0-ffffffff8152fdeb: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8155c410)
Location: drivers/regulator/devres.c:131
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff8155c410-ffffffff8155c44b: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81570fa0)
Location: drivers/regulator/devres.c:112
Inline: True
```
**Symbols:**

```
ffffffff81570fa0-ffffffff81570fca: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff815d5240)
Location: drivers/regulator/devres.c:112
Inline: True
```
**Symbols:**

```
ffffffff815d5240-ffffffff815d526a: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8160e040)
Location: drivers/regulator/devres.c:112
Inline: True
```
**Symbols:**

```
ffffffff8160e040-ffffffff8160e06a: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8162ab60)
Location: drivers/regulator/devres.c:112
Inline: True
```
**Symbols:**

```
ffffffff8162ab60-ffffffff8162ab8a: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8165e8ec)
Location: drivers/regulator/devres.c:107
Inline: True
```
**Symbols:**

```
ffffffff8165e8ec-ffffffff8165e8ff: devm_regulator_put.cold (STB_LOCAL)
ffffffff8165e6c0-ffffffff8165e6ec: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81680e90)
Location: drivers/regulator/devres.c:107
Inline: True
```
**Symbols:**

```
ffffffff81680e90-ffffffff81680eba: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81732010)
Location: drivers/regulator/devres.c:107
Inline: True
```
**Symbols:**

```
ffffffff81732010-ffffffff8173203a: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8174e130)
Location: drivers/regulator/devres.c:107
Inline: True
```
**Symbols:**

```
ffffffff8174e130-ffffffff8174e15a: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81731cb0)
Location: drivers/regulator/devres.c:107
Inline: True
```
**Symbols:**

```
ffffffff81731cb0-ffffffff81731cda: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff817b19e0)
Location: drivers/regulator/devres.c:107
Inline: False
```
**Symbols:**

```
ffffffff817b19e0-ffffffff817b1a0a: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff818ed170)
Location: drivers/regulator/devres.c:107
Inline: False
```
**Symbols:**

```
ffffffff818ed170-ffffffff818ed1a8: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a44fe4)
Location: drivers/regulator/devres.c:166
Inline: True
Inline callers:
  - drivers/regulator/devres.c:_devm_regulator_get_enable
```
**Symbols:**

```
ffffffff81a446f0-ffffffff81a44728: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a8f19b)
Location: drivers/regulator/devres.c:166
Inline: True
Inline callers:
  - drivers/regulator/devres.c:_devm_regulator_get_enable
```
**Symbols:**

```
ffffffff81a8e8a0-ffffffff81a8e8d8: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81ae1a0b)
Location: drivers/regulator/devres.c:166
Inline: True
Inline callers:
  - drivers/regulator/devres.c:_devm_regulator_get_enable
```
**Symbols:**

```
ffffffff81ae1110-ffffffff81ae1148: devm_regulator_put (STB_GLOBAL)
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
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffff80001084abe8)
Location: drivers/regulator/devres.c:107
Inline: True
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffff80001084abe8-ffff80001084ac30: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (c095406c)
Location: drivers/regulator/devres.c:107
Inline: True
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/clk/tegra/clk-tegra124-dfll-fcpu.c:tegra124_dfll_fcpu_probe
```
**Symbols:**

```
c095406c-c09540c0: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (c0000000008e85e0)
Location: drivers/regulator/devres.c:107
Inline: True
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
c0000000008e85e0-c0000000008e8638: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffe00052a826)
Location: drivers/regulator/devres.c:107
Inline: True
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffe00052a826-ffffffe00052a866: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81646910)
Location: drivers/regulator/devres.c:107
Inline: True
```
**Symbols:**

```
ffffffff81646910-ffffffff8164693a: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81626d70)
Location: drivers/regulator/devres.c:107
Inline: True
```
**Symbols:**

```
ffffffff81626d70-ffffffff81626d9a: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81674cd0)
Location: drivers/regulator/devres.c:107
Inline: True
```
**Symbols:**

```
ffffffff81674cd0-ffffffff81674cfa: devm_regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8168f330)
Location: drivers/regulator/devres.c:107
Inline: True
```
**Symbols:**

```
ffffffff8168f330-ffffffff8168f35a: devm_regulator_put (STB_GLOBAL)
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
