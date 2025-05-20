# Function: <code>regmap_register_patch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81567170)
Location: drivers/base/regmap/regmap.c:2772
Inline: False
Direct callers:
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff81567170-ffffffff8156728e: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815bbbb0)
Location: drivers/base/regmap/regmap.c:2778
Inline: False
Direct callers:
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff815bbbb0-ffffffff815bbcc2: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815eafc0)
Location: drivers/base/regmap/regmap.c:2816
Inline: False
Direct callers:
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff815eafc0-ffffffff815eb0d2: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815ff900)
Location: drivers/base/regmap/regmap.c:2823
Inline: False
Direct callers:
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff815ff900-ffffffff815ffa1b: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81667c10)
Location: drivers/base/regmap/regmap.c:2902
Inline: False
Direct callers:
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff81667c10-ffffffff81667d37: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a31a0)
Location: drivers/base/regmap/regmap.c:2857
Inline: False
Direct callers:
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff816a31a0-ffffffff816a32c7: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c3bc0)
Location: drivers/base/regmap/regmap.c:3017
Inline: False
Direct callers:
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff816c3bc0-ffffffff816c3ce7: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fea50)
Location: drivers/base/regmap/regmap.c:3014
Inline: False
Direct callers:
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff816fea50-ffffffff816feb87: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81722e70)
Location: drivers/base/regmap/regmap.c:3021
Inline: False
Direct callers:
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff81722e70-ffffffff81722fa7: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817df010)
Location: drivers/base/regmap/regmap.c:3039
Inline: False
Direct callers:
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff817df010-ffffffff817df147: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f40e0)
Location: drivers/base/regmap/regmap.c:3196
Inline: False
Direct callers:
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff817f40e0-ffffffff817f4217: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d8950)
Location: drivers/base/regmap/regmap.c:3196
Inline: False
Direct callers:
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff817d8950-ffffffff817d8a87: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3237
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff81d04d09-ffffffff81d04d31: regmap_register_patch.cold (STB_LOCAL)
ffffffff818640a0-ffffffff818641f0: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3254
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff81ecd738-ffffffff81ecd769: regmap_register_patch.cold (STB_LOCAL)
ffffffff819ac2e0-ffffffff819ac447: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3408
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff82099423-ffffffff8209944c: regmap_register_patch.cold (STB_LOCAL)
ffffffff81b1f900-ffffffff81b1fa4f: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3437
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff8211a4b6-ffffffff8211a4e7: regmap_register_patch.cold (STB_LOCAL)
ffffffff81b6eb00-ffffffff81b6ec85: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3317
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff821f833d-ffffffff821f836e: regmap_register_patch.cold (STB_LOCAL)
ffffffff81bc2700-ffffffff81bc2885: regmap_register_patch (STB_GLOBAL)
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
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010917850)
Location: drivers/base/regmap/regmap.c:3021
Inline: False
Direct callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffff800010917850-ffff80001091798c: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fd6c4)
Location: drivers/base/regmap/regmap.c:3021
Inline: False
Direct callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
c09fd6c4-c09fd7f8: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009ba8e0)
Location: drivers/base/regmap/regmap.c:3021
Inline: False
Direct callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
c0000000009ba8e0-c0000000009baab4: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000598056)
Location: drivers/base/regmap/regmap.c:3021
Inline: False
Direct callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffe000598056-ffffffe00059815a: regmap_register_patch (STB_GLOBAL)
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
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e91a0)
Location: drivers/base/regmap/regmap.c:3021
Inline: False
Direct callers:
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
```
**Symbols:**

```
ffffffff816e91a0-ffffffff816e92d7: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c37e0)
Location: drivers/base/regmap/regmap.c:3021
Inline: False
Direct callers:
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
```
**Symbols:**

```
ffffffff816c37e0-ffffffff816c3917: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81716330)
Location: drivers/base/regmap/regmap.c:3021
Inline: False
Direct callers:
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff81716330-ffffffff81716467: regmap_register_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regmap_register_patch(struct regmap *map, const struct reg_sequence *regs, int num_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817315d0)
Location: drivers/base/regmap/regmap.c:3021
Inline: False
Direct callers:
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm5110-tables.c:wm5110_patch
  - drivers/mfd/wm8998-tables.c:wm8998_patch
  - drivers/mfd/cs47l24-tables.c:cs47l24_patch
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff817315d0-ffffffff81731707: regmap_register_patch (STB_GLOBAL)
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
