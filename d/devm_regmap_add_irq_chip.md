# Function: <code>devm_regmap_add_irq_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff815c16e0)
Location: drivers/base/regmap/regmap-irq.c:740
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/sec-irq.c:sec_irq_init
```
**Symbols:**

```
ffffffff815c16e0-ffffffff815c17b5: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff815f0b20)
Location: drivers/base/regmap/regmap-irq.c:740
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/sec-irq.c:sec_irq_init
```
**Symbols:**

```
ffffffff815f0b20-ffffffff815f0bf5: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81604c60)
Location: drivers/base/regmap/regmap-irq.c:752
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/sec-irq.c:sec_irq_init
```
**Symbols:**

```
ffffffff81604c60-ffffffff81604d3b: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8166d040)
Location: drivers/base/regmap/regmap-irq.c:752
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/sec-irq.c:sec_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff8166d040-ffffffff8166d11b: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816a8a90)
Location: drivers/base/regmap/regmap-irq.c:752
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/sec-irq.c:sec_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff816a8a90-ffffffff816a8b6b: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816c9670)
Location: drivers/base/regmap/regmap-irq.c:814
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/sec-irq.c:sec_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff816c9670-ffffffff816c974b: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817048b0)
Location: drivers/base/regmap/regmap-irq.c:898
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff817048b0-ffffffff8170498b: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81728c00)
Location: drivers/base/regmap/regmap-irq.c:893
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81728c00-ffffffff81728cdb: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817e54a0)
Location: drivers/base/regmap/regmap-irq.c:962
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/sec-irq.c:sec_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff817e54a0-ffffffff817e54ce: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817fa3e0)
Location: drivers/base/regmap/regmap-irq.c:996
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/sec-irq.c:sec_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff817fa3e0-ffffffff817fa440: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817df0f0)
Location: drivers/base/regmap/regmap-irq.c:1064
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/sec-irq.c:sec_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff817df0f0-ffffffff817df150: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8186ab60)
Location: drivers/base/regmap/regmap-irq.c:1063
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff8186ab60-ffffffff8186abc0: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff819b3820)
Location: drivers/base/regmap/regmap-irq.c:1065
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff819b3820-ffffffff819b3893: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b28520)
Location: drivers/base/regmap/regmap-irq.c:1248
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81b28520-ffffffff81b28593: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b78130)
Location: drivers/base/regmap/regmap-irq.c:1060
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81b78130-ffffffff81b781a3: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcbf30)
Location: drivers/base/regmap/regmap-irq.c:1060
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81bcbf30-ffffffff81bcbfa3: devm_regmap_add_irq_chip (STB_GLOBAL)
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
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffff80001091e538)
Location: drivers/base/regmap/regmap-irq.c:893
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
**Symbols:**

```
ffff80001091e538-ffff80001091e638: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (c0a0393c)
Location: drivers/base/regmap/regmap-irq.c:893
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
**Symbols:**

```
c0a0393c-c0a03a24: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (c0000000009c3460)
Location: drivers/base/regmap/regmap-irq.c:893
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
**Symbols:**

```
c0000000009c3460-c0000000009c35a0: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffe00059dbd0)
Location: drivers/base/regmap/regmap-irq.c:893
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
**Symbols:**

```
ffffffe00059dbd0-ffffffe00059dc80: devm_regmap_add_irq_chip (STB_GLOBAL)
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
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816ee9e0)
Location: drivers/base/regmap/regmap-irq.c:893
Inline: False
```
**Symbols:**

```
ffffffff816ee9e0-ffffffff816eeabb: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816c9020)
Location: drivers/base/regmap/regmap-irq.c:893
Inline: False
```
**Symbols:**

```
ffffffff816c9020-ffffffff816c90fb: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8171c0c0)
Location: drivers/base/regmap/regmap-irq.c:893
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff8171c0c0-ffffffff8171c19b: devm_regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devm_regmap_add_irq_chip(struct device *dev, struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81737420)
Location: drivers/base/regmap/regmap-irq.c:893
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81737420-ffffffff817374fb: devm_regmap_add_irq_chip (STB_GLOBAL)
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
